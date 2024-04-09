<template>
    <header>
        <img :src="hero" alt="Futaba">
    </header>
</template>

<script>
    export default {
        name:'AppHero',
        data() {
            return {
                hero: '/public/img/Futaba.jpg'
            }
        }
        
    }
</script>

<style scoped>
img {
    width: 50%;
}
</style>