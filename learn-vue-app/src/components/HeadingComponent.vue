<template>
    <h1 class="heading"> {{ title }}</h1>
    <p class="description">{{ description }}</p>
</template>

<script lang="ts">
export default {
    name: 'HeadingComponent',
    data() {
        return {
            title: 'Welcome to Vue Restaurant',
            description: 'A Vue.js project to learn Vue.js',
        };
    },
};
</script>

<style scoped>
    .heading {
        color: #178c03;
        font-size: 2em;
    }

    .description {
        color: #b76210;
        font-size: 1em;
    }
</style>