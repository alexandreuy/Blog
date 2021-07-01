<template>
    <div>
        <h2> {{ title }}</h2>
        <p>{{ contenu }} </p>
    </div>
</template>

<script>
    export default {
        name: 'Article',
        props: ["title", "contenu"]
    }
</script>

<style lang="scss" scoped>

</style>