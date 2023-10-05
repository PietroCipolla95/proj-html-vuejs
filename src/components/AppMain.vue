<script>
import AppWorkCulture from './AppWorkCulture.vue';
import AppSkills from './AppSkills.vue';
import AppCourses from './AppCourses.vue';
import AppWave from './AppWave.vue';
import AppTestimonials from './AppTestimonials.vue';



export default {
    name: 'AppMain',

    components: {
        AppWorkCulture,
        AppSkills,
        AppCourses,
        AppWave,
        AppTestimonials
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





    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>