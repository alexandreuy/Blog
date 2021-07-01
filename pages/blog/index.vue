<template>
    <div>
        <nuxt-link to="/"> Accueil </nuxt-link>
        <Article title="Hello" contenu="World" />
    </div>
</template>

<script>
import Article from '../../components/Article.vue'
    export default {
        name: 'Blog',
        components:{
           Article 
        }
    }
</script>

<style lang="scss" scoped>

</style>