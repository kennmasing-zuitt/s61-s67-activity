<script>
import BannerComponent from "./components/BannerComponent.vue";
import NavbarComponent from "./components/NavbarComponent.vue";
import HighlightComponent from "./components/HighlightComponent.vue";

export default {
    name: "App",
    components: {
        NavbarComponent,
        BannerComponent,
        HighlightComponent
    },
};
</script>

<template>
    <NavbarComponent />
    <BannerComponent />
    <HighlightComponent />
</template>

<style scoped>
h1 {
    font-family: serif;
    font-style: normal;
    font-weight: 700;
    font-size: 3rem;
}
</style>
