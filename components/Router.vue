<template>
  <div @click="click">
    <component :is="getPage()"></component>
  </div>
</template>

<script>
export default {
  props: ['routes'],

  data: () => ({
    href: location.pathname
  }),

  methods: {
    getPage() {
      return this.routes[this.href] || this.routes.default;
    },

    click(event) {
      if (event.target.tagName !== 'A') return;

      const href = event.target.getAttribute('href');
      if (!href.startsWith('/')) return;

      event.preventDefault();
      history.pushState(null, null, href);
      this.href = href;
    }
  }
}
</script>
