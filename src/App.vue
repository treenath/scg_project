<template>
  <div>
    <app-header></app-header>
    <app-body></app-body>
    <hr>
    <router-view/>
    <hr>
    <app-footer></app-footer>  
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Body from '@/components/Body.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    'app-header': Header,
    'app-body': Body,
    'app-footer': Footer
  },
  data() {
    return {

    }
  }
}
</script>

<style>

</style>
