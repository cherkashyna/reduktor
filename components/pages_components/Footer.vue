<template>
  <footer>
    <div class="container">
      <img src="" alt />
      <div class="footer-text">
        <p>&copy; 2019 Ремонт редуктора</p>
        <p>Все права защищены.</p>
        <small>Developed by Diana Cherkashyna</small>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  height: 20vh;
  background: #00bce4;
}
.container {
  display: flex;
  height: 100%;
  justify-content: space-between;
  align-items: center;
}
.footer-text{
  margin-right: 10px;
}
img {
  display: block;
  margin-left: 70px;
}
p, small {
  color: #fff;
  line-height: 2em;
}
small {font-size: 0.8em;}
</style>