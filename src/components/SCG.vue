<template>
  <div>
    <b-button variant="outline-primary" @click="modalShow = !modalShow">Click me</b-button>
    <b-modal v-model="modalShow">Hello SCG!</b-modal>
  </div>
</template>

<script>
export default {
  name: 'scg',
  data () {
    return {
        modalShow: false
    }
  }
}
</script>

<style scoped>
</style>
