<template>
  <div id="app">
    <myTitle />
    <heroComp />
  </div>
</template>

<script>
import myTitle from './components/myTitle.vue'
import heroComp from './components/heroComp.vue'

export default {
  name: 'App',
  components: {
    myTitle,
    heroComp
  }
}
</script>

<style lang="scss">
#app {

}
</style>
