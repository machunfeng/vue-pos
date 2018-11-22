<template>
  <div id="app">
    <leftNav></leftNav>
    <router-view/>
  </div>
</template>

<script>
import leftNav from '@/components/common/leftNav'
export default {
  name: 'app',
  components: {
    leftNav
  }
}
</script>

<style lang="scss">

</style>
