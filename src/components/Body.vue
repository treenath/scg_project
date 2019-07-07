<template>
  <div>
    <div>
        <b-nav small>
            <b-nav-item active><b-link :to="'/'">Home</b-link></b-nav-item>
            <b-nav-item active><b-link :to="'/scg'">SCG</b-link></b-nav-item>
            <b-nav-item disabled>Function</b-nav-item>
            <b-nav-item active><b-link :to="'/cv'">CV</b-link></b-nav-item>
        </b-nav>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'This is Body'
        }
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
