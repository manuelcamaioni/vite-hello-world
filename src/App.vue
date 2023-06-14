<template>
    <AppTitle />
    <Hero />
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import Hero from "./components/HeroApp.vue";
export default {
    components: {
        AppTitle,
        Hero,
    },

    data() {
        return {};
    },
};
</script>

<style>
div {
    margin: 0;
    width: 100%;
}
</style>
