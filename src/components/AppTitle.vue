<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'La mia prima app con Vite!',
        };
    },
};

</script>

<template>
    <h1> {{ title }}</h1>
    <p>Sono il paragrafo di AppTitle</p>
</template>

<style scoped>
    h1{
        color: blue;
    }

    p{
        color: red;
    }
</style>