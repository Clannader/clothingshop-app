<template>
  <div>
    <router-view></router-view>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import AppFooter from './components/AppFooter'
  export default {
    name: 'HomePage',
    components: {
      AppFooter
    }
  }
</script>

<style scoped>

</style>
