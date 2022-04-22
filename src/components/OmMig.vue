<template>
  <div class="OmMig">
    <div class="ConTainer">
      <div class="Box_A">
        <p>Jeg kommer oprindeligt fra Næstved, men efter de store er fløjet fra reden, besluttede jeg mig for at kaste mig ud i noget helt nyt og startede på multimediedesigner uddannelse i Esbjerg, den frihed til at kunne kaste anker 
        lige der hvor livet fører mig hen, giver mig mulighed for at kunne flytte efter det helt rigtige job. <br> Jeg er uddannet lærer og har altid arbejdet med mennesker, og i forbindelse med det har jeg været på flere kurser indenfor neuropsykologi, 
        jeg synes at det er spændende at prøve og forstå hvorfor folk gøre som de gør. <br> I min fritid har jeg altid haft en stor passion for kreative sysler såsom tegning, maling, design og fotografering, så at finde en uddannelse hvor alt 
        dette bliver kombineret har været som at finde hjem. <br> Der er ingen tvivl om, at jeg efter mange spændende omveje, har fundet det rigtigt studie som på fineste vis forener mine kreative interesser, brugeradfærd og muligheden for at 
        arbejde sammen med andre passionerede mennesker. </p>
      </div>
      <div class="Box_B">
          <img src="../assets/Unicorn.gif" alt="">
      </div>
        
    </div>
  </div>

</template>

<script>
export default {
  name: 'OmMig',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.OmMig {
  display: flex;
  justify-content: center;
  align-content: center;
  height: 100vh;
  .ConTainer {
   display: flex;
   flex-direction: row;
   justify-content: center;
   align-content: space-around;
  }
  .Box_A {
   display: flex;
   align-content: center;
   text-align: left;
   margin: 40px;
   width: auto;
   font-size: larger;
   line-height: 1.2;
  }
  .Box_B {
   display: flex;
   justify-items: center;
   align-content: center;
   width: auto;
   height: 100vh;
   img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    height: 90%;
    }
  }
}
</style>