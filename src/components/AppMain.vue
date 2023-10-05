<script>
import AppWorkCulture from './AppWorkCulture.vue';
import AppSkills from './AppSkills.vue';
import AppCourses from './AppCourses.vue';
import AppWave from './AppWave.vue';
import AppTestimonials from './AppTestimonials.vue';
import AppTransformSection from './AppTransformSection.vue';


export default {
    name: 'AppMain',

    components: {
        AppWorkCulture,
        AppSkills,
        AppCourses,
        AppWave,
        AppTestimonials,
        AppTransformSection,
    }

}
</script>
<template>
    <main>
        <AppWorkCulture />

        <AppSkills />

        <AppCourses />

        <AppWave />

        <AppTestimonials />

        <AppTransformSection />





    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>