<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <OmMig msg="Hvem er jeg?"/>
    <OpGaver msg="Tidligere opgaver"/>
    <CV msg="CV"/>
    <KontaktInfo msg="Kontakt mig"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import OmMig from '@/components/OmMig.vue'
import OpGaver from '@/components/OpGaver.vue'
import CV from '@/components/CV.vue'
import KontaktInfo from '@/components/KontaktInfo.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    OmMig,
    OpGaver,
    CV,
    KontaktInfo
}
}
</script>
