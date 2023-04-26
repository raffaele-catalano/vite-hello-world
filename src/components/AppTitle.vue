<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'This is my First App with Vite',
        }
    }
}
</script>

<template>
    <h2>{{ title }}</h2>
</template>

<style scoped>
    h2 {
        color: white;
        will-change: filter;
        transition: filter 300ms;
    }

    h2:hover {
        filter: drop-shadow(0 0 1em rgb(213, 19, 58));
        cursor: pointer;
    }
</style>