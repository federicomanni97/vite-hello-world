<template>
<header>
  <h1><AppTitleComponent/></h1>
</header>
</template>

<script>
import AppTitleComponent from './components/AppTitleComponent.vue'
export default {
    name: 'App',
    components: {
        AppTitleComponent,
    },
  data() {
    
    return {
      
    }
  }
}
</script>

<style lang="css" scoped>
      h1{
        color: yellow;
      }
</style>