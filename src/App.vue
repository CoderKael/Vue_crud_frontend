<template>
  <HeaderVue title="CRUD"/>
  <router-view>
    
  </router-view>
</template>

<script>
import HeaderVue from './components/Header.vue';
export default {
  name: 'App',
  components: {
    HeaderVue
  }
}
</script>

<style>

</style>
