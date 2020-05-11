<template>
  <div class="l-container">
    <Header />
    <Main>
      <section>
        <Hero />
        <About />
      </section>
    </Main>
    <Footer />
  </div>
</template>

<script>
  import Hero from '@/components/productName/ProductNameHero.vue'
  import About from '@/components/productName/ProductNameAbout.vue'

  export default {
    name: 'Product Name',
    components: {
    },
    data () {
      return {
        title: 'Product Name',
      }
    },
  }
</script>

<style scoped lang="scss">
</style>
