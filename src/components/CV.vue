<template>
  <div class="CV">
    <h1>{{ msg }}</h1>
  </div>

</template>

<script>
export default {
  name: 'CV',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.CV {
    height: 100vh;
}
</style>

