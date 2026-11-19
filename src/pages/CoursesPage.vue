<template>
    <div class="container my-5">
        <div class="row">
            <div class="col text-center">
                <h1 class="text-center text-primary mt-5 pt-3 mb-2">Courses</h1>
                <p class="text-center mb-4 pb-2">Select a course to enroll in!</p>
            </div>
        </div>
        <div class="row g-4">
            <div class="col-md-4"><CourseComponent /></div>
            <div class="col-md-4"><CourseComponent2 /></div>
            <div class="col-md-4"><CourseComponent3 /></div>
            <div class="col-md-4"><CourseComponent4 /></div>
            <div class="col-md-4"><CourseComponent5 /></div>
            <div class="col-md-4"><CourseComponent6 /></div>
        </div>
    </div>
</template>

<script>
import CourseComponent from "../components/CourseComponent.vue";
import CourseComponent2 from "../components/CourseComponent2.vue";
import CourseComponent3 from "../components/CourseComponent3.vue";
import CourseComponent4 from "../components/CourseComponent4.vue";
import CourseComponent5 from "../components/CourseComponent5.vue";
import CourseComponent6 from "../components/CourseComponent6.vue";

export default {
    name: "CoursesPage",
    components: {
        CourseComponent,
        CourseComponent2,
        CourseComponent3,
        CourseComponent4,
        CourseComponent5,
        CourseComponent6,
    },
};
</script>

<style></style>
