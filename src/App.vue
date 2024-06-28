<template>
  <div class="mb-4">
    <Header />
  </div>
  <div>
    <Main />
  </div>
  <div class="mt-4">
    <Footer />
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import Main from './components/Main.vue'
  import Footer from './components/Footer.vue'
  export default {
    name: 'App',
    components: {
      Header,
      Main,
      Footer
    },
    data() {
      return {
        
      }
    }
  }
</script>

<style lang="scss" scoped></style>
