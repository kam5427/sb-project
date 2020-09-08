<template>
  <div>
    <Header/>
    <nuxt />

  </div>
</template>

<script>
  import Header from '~/components/Header.vue'

  export default {
    components: {
      Header
    }
  }
</script>
<style>
body {
  background-image: url('~assets/svg/background.svg');
  height: 970px;
  background-repeat:no-repeat;
}
</style>
