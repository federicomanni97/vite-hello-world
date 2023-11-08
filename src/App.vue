<template>
<header>
  <h1><AppTitleComponent/></h1>
  <appHero/>
</header>
</template>

<script>
import AppHero from './components/appHero.vue'
import AppTitleComponent from './components/AppTitleComponent.vue'
export default {
    name: 'App',
    components: {
        AppTitleComponent,
        appHero
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