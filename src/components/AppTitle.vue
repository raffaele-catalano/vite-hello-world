<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'This is my First App with',
        }
    }
}
</script>

<template>
    <h2>{{ title }} <span>Vite</span></h2>
</template>

<style scoped>

    h2 {
        color: white;
        will-change: filter;
        transition: filter 300ms;
    }

    h2:hover {
        filter: drop-shadow(1px 1px 1em rgb(147, 106, 254));
        cursor: pointer;
    }

    span {
        color: rgb(147, 106, 254);
    }

</style>