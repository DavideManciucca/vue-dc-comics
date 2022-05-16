<template>
  <header>
    <div><img src="../assets/img/dc-logo.png" alt=""></div>
    <div>
      <ul>
        <li> <a href="#">CHARACTERS</a> </li>
        <li><a href="#" class="active">COMICS</a> </li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name:'HeaderComp'
}
</script>

<style lang="scss" scoped>
header{
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 5px;
  div ul{
  list-style: none;  
  display: flex;
  .active{
    color:blue;
    border-bottom: 1px solid blue;
  }
  }
  ul li a{
    color: grey;
    text-decoration: none;
    padding: 10px;
  }

}

</style>