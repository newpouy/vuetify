/* eslint-disable no-console */
<template>
  <button>MYBTN</button>
</template>

<script>
export default {
  name: 'MyBtn' ,
  beforeCreate() {
    console.log('beforeCreate MyBtn')
  },
  created() {
    console.log('created MyBtn')
  },
  beforeMount() {
    console.log('beforeMount MyBtn')
  },
  mounted() {
    console.log('mounted MyBtn')
  },
  beforeDestroy() {
    console.log('beforeDestroy MyBtn')
  },
  destroyed() {
    console.log('destroyed MyBtn')
  }
}
</script>

<style scoped>

</style>