<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Footer from '@/components/footer/Footer'
import Header from '@/components/header/Header'
export default {
      components: {
        Footer,
        Header
  },

}
</script>