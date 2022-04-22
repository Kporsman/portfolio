<template>
  <div class="HelloWorld">
    <div id="logo"><img src="../assets/logo_orange_new.svg" alt=""></div>
    <h1> Kathrine Lunde Porsman </h1>
    <div class="cont">
      <div class="soci_1">
        <a href="https://www.linkedin.com/in/kathrine-lunde-porsman-4a72b5225/"> <img src="../assets/linkedin.png" alt=""></a>
      </div>
      <div class="soci_2"> 
        <a href="#"> <img src="../assets/instagram.png" alt=""></a>
      </div>
      <div class="soci_3">
        <a href="#"> <img src="../assets/cv_k.png" alt=""></a>
      </div> 
    </div> 
    
    
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.HelloWorld {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  height: 120px;
  align-items: center;
  
  #logo {
    height: 120px;
    display: flex;
    box-sizing: border-box;
    float: left;
    margin-top: 5px;
    margin-left: 10px;
    
  }
  .cont {
     display: flex;
     justify-content: space-between;
     flex-direction: row;
     height: 120px;
     align-items: center;
     .soci_1 img {
       display: flex;
       justify-content: center;
       height: 50px;
       margin: 10px;
      }
     .soci_2 img {
       display: flex;
       justify-content: center;
       height: 50px;
       margin: 10px;
      }
      .soci_3 img {
       display: flex;
       justify-content: center;
       height: 50px;
       margin: 10px;
      }
  }
  
}

</style>