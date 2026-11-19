<script>
import NavbarComponent from "./components/NavbarComponent.vue";
import HighlightComponent from "./components/HighlightComponent.vue";

import HomePage from "./pages/HomePage.vue";


export default {
    name: "App",
    components: {
        NavbarComponent,

        BannerComponent,
        HighlightComponent

        HomePage,

    },
};
</script>

<template>
    <NavbarComponent />
    <BannerComponent />
    <HighlightComponent />
    <HomePage />
</template>

<style scoped>
h1 {
    font-family: serif;
    font-style: normal;
    font-weight: 700;
    font-size: 3rem;
}
</style>
