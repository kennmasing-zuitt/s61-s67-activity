<script>
import NavbarComponent from "./components/NavbarComponent.vue";
import HomePage from "./pages/HomePage.vue";

export default {
    name: "App",
    components: {
        NavbarComponent,
        HomePage,
    },
};
</script>

<template>
    <NavbarComponent />
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
