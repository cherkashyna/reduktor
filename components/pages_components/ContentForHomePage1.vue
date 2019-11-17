<template>
          
  <div class="container">

    <div class="col">
      <p class="icon">
        <i class="fas fa-envelope"></i>
      </p>
      <h3>e-mail:</h3>
      <p>alligator2611@gmail.com</p>
      <p> </p>
    </div>
    <div class="col">
      <p class="icon">
        <i class="fas fa-map-marker-alt"></i>
      </p>
      <h3>Мы находимся</h3>
      <p>Украина</p>
      <p>Харьков</p>
    </div>
    <div class="col">
      <p class="icon">
        <i class="fas fa-phone-square"></i>
      </p>
      <h3>Звоните нам</h3>
      <p>068-190-70-54<br>095-671-46-55</p>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  position: relative;
}
.col {
  width: 33%;
  margin-right: 1%;
  min-height: 350px;
  padding: 20px 50px 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.col:last-child {
  margin-right: 0;
}
/*.col:first-child,
.col:last-child {
  background: url(/img/top2.png);
}
.col:nth-child(2) {
  background: url(/img/top1.png);
}*/
.col .icon {
  font-size: 60px;
  color: #00bce4;
  border: dotted 2px #00bce4;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 20px;
}
</style>