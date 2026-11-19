<script>
import NavbarComponent from "./components/NavbarComponent.vue";
import CoursesPage from "./pages/CoursesPage.vue";
import HomePage from "./pages/HomePage.vue";

export default {
    name: "App",
    components: {
        NavbarComponent,
        HomePage,
        CoursesPage,
    },
};
</script>

<template>
    <NavbarComponent />
    <HomePage />
    <CoursesPage />
</template>

<style scoped>
h1 {
    font-family: serif;
    font-style: normal;
    font-weight: 700;
    font-size: 3rem;
}
</style>
