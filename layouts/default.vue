<template>
  <div>
    <Header />
    <NavBar />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from '~/components/Header'
import NavBar from '~/components/NavBar'
import Footer from '~/components/Footer'

export default {
  components: {
    Header,
    NavBar,
    Footer,
  },
}
</script>
