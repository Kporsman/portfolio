<template>
  <div class="OpGaver">
    <h1>{{ msg }}</h1>
    <div class="box_1">  </div>
    <div class="box_2">  </div>
    <div class="box_3">  </div>
  </div>

</template>

<script>
export default {
  name: 'OpGaver',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.OpGaver {
  display: flex;
  flex-direction: column;
  justify-items: center;
  align-content: space-around;
  margin: 10px;
  background-color:#1D2428;
     
}
.box_1 {
    background-color: #6fb6c4;
    opacity: 90%;
    height: 200px;
    width: auto;
    margin: 20px;
  }
  .box_2 {
    background-color: #357a87;
    opacity: 90%;
    height: 200px;
    width: auto;
    margin: 20px;
  }  
  .box_3 {
    background-color: #a96fc4;
    opacity: 90%;
    height: 200px;
    width: auto;
    margin: 20px;
  }       

</style>