<script>
import AppWorkCulture from './AppWorkCulture.vue';
import AppSkills from './AppSkills.vue';
import AppCourses from './AppCourses.vue';
import AppWave from './AppWave.vue'



export default {
    name: 'AppMain',

    components: {
        AppWorkCulture,
        AppSkills,
        AppCourses,
        AppWave,
    }

}
</script>
<template>
    <main>
        <AppWorkCulture />

        <AppSkills />

        <AppCourses />

        <AppWave />



    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>