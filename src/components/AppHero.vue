<template>
    <div>
        <img :src="img">
    </div>
</template>

<script>
export default {
    name: 'AppHero',
    data() {
        
        return {
            img: "../../public/img/paesaggioimmagine.jpg"
        }
    }
}
</script>

<style lang="css" scoped>
</style>