<template>
    <section class="section">
        <div class="container">
            <Header />
            <hr>
            <router-view></router-view>
            <Footer></Footer>
        </div>
    </section>
</template>

<script>
import Header from '../components/Navbar'
import Footer from '../components/Footer'

export default {
  name: 'layout',
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="sass">
    .section
        padding: 0 1.5rem !important

    hr
        margin: 0 !important

    .container
        height: 100vh

    .page
        height: 75%
</style>
