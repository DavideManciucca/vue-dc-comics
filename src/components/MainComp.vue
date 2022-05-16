<template>
  <main>
    <div class="content">-->Content Goes Here ! </div>
    <div class="banner">
      <div class="ban-box"><div><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div> DIGITAL COMICS</div>
      <div class="ban-box"><div><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div> DC MERCHANDISE</div>
      <div class="ban-box"><div><img src="../assets/img/buy-comics-subscriptions.png" alt=""></div> SUBSCRIPTION</div>
      <div class="ban-box"><div><img src="../assets/img/buy-comics-shop-locator.png" alt=""></div> COMING SHOP LOCATOR</div>
      <div class="ban-box"><div><img src="../assets/img/buy-dc-power-visa.svg" alt=""></div> DC POWER VISA</div>

    </div>
  </main>
</template>

<script>
export default {
  name:'MainComp'
}
</script>

<style lang="scss" scoped>
.content{
  height: 100px;
  background-color: rgb(34, 33, 33);
  color: white;
}
.banner{
  display: flex;
  height: 140px;
  color:white;
  background-color: #0c7cec;
  justify-content: space-around;
}.ban-box{
  display: flex;
  align-items: center;
}.ban-box img{
  height: 50px;
}


</style>