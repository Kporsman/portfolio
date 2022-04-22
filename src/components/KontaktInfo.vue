<template>
  <div class="KontaktInfo">
    <h1>{{ msg }}</h1>
  </div>

</template>

<script>
export default {
  name: 'KontaktInfo',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.KontaktInfo {
    height: 100vh;
}
</style>