<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {

  },
  created() {
    window.Chargebee.init({
      site: "mens-test",
      publishableKey: "test_G8QpxfxkAfYxRpMgdzncd3bKGsB0VvEIj"
    })
  }
}
</script>

<style>
body {
  margin: 0;
}
</style>