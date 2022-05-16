<template>
  <footer>
    <div class="wrapper">
      <div class="col-list">
        <div class="title">DC COMICS</div>
        <div>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </div>
        <div class="title">SHOP</div>
         <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
         </ul>
      </div>
      

            
      <div class="col-list">
        <div class="title">DC</div>
        <div>
          <ul>
            <li><a href="#">Therms of use</a></li>
            <li><a href="#">Privacy policy</a></li>
            <li><a href="#">Ad Choice</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscription</a></li>
            <li><a href="#">Talent Workshop</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Rating</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        
      </div>


      <div class="col-list">
        <div class="title">SITES</div>
        <div>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
           
          </ul>
        </div>
        
      </div>

    </div>
  </footer>
</template>

<script>
export default {
  name:'FooterComp'
}
</script>

<style lang="scss" scoped>
footer{
  height: 400px;
  background-image: url(../assets/img/footer-bg.jpg);
 
}.wrapper{
  display: flex;
  justify-content: space-between;
  height: 75%;
  width:500px;
  background-color: red;
}.col-list{
  padding-top: 20px;
  padding-left:20px ;
  width: calc(100% / 3);
  align-items: center;
}.title{
  color: white;
  font-weight: bold;
}ul li{
  list-style: none;
}a{
  text-decoration: none;
  color: grey;
  font-size: 12px;
}



</style>