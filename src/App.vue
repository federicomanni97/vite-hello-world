<template>
<header>
  <h1><AppTitleComponent/></h1>
  <AppHero/>
</header>
</template>

<script>
import AppHero from './components/AppHero.vue'
import AppTitleComponent from './components/AppTitleComponent.vue'
export default {
    name: 'App',
    components: {
        AppTitleComponent,
        AppHero,
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