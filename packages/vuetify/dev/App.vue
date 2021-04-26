<template>
  <v-app>
    <v-main>
      <playground></playground>
    </v-main>
  </v-app>
</template>

<script>
  import Playground from './Playground'

  export default {
    components: {
      Playground,
    },
      beforeCreate() {
      console.log('beforeCreate App')
    },
    created() {
      console.log('created App')
    },
    beforeMount() {
      console.log('beforeMount App')
    },
    mounted() {
      console.log('mounted App')
    },
    beforeDestroy() {
      console.log('beforeDestroy App')
    },
    destroyed() {
      console.log('destroyed App')
    }
  }
</script>
