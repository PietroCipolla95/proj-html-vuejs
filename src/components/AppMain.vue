<script>
import AppWorkCulture from './AppWorkCulture.vue';
import AppSkills from './AppSkills.vue';
import AppCourses from './AppCourses.vue'


export default {
    name: 'AppMain',

    components: {
        AppWorkCulture,
        AppSkills,
        AppCourses,
    }

}
</script>
<template>
    <main class="container my_width">
        <AppWorkCulture />

        <AppSkills />

        <AppCourses />



    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>