<template>
    <BannerComponent />
    <HighlightsComponent />
</template>

<script>
import BannerComponent from "../components/BannerComponent.vue";
import HighlightsComponent from "../components/HighlightsComponent.vue";

export default {
    name: "HomePage",
    components: {
        BannerComponent,
        HighlightsComponent,
    },
};
</script>

<style></style>
