<script>
import BannerComponent from "./components/BannerComponent.vue";
import NavbarComponent from "./components/NavbarComponent.vue";

export default {
    name: "App",
    components: {
        NavbarComponent,
        BannerComponent,
    },
};
</script>

<template>
    <NavbarComponent />
    <BannerComponent />
</template>

<style scoped>
h1 {
    font-family: serif;
    font-style: normal;
    font-weight: 700;
    font-size: 3rem;
}
</style>
