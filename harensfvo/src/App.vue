<template>
  <v-app light>
    <Navbar />
    <v-content class="site-body">
      <router-view></router-view>
    </v-content>
    <Footer />
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: {
    Navbar,
    Footer    
  },
  data () {
    return {
      //
    }
  }
}
</script>

<style>

  @media screen and (min-width: 900px) {
    .site-body {
      max-width: 1440px;
      margin: 0 auto;
    }
  }

  em {
    color: #26d07c;
  }

  .containerStyle {
    width: 100%;
    padding: 20px;
    margin: 30px 30px;
  }

</style>