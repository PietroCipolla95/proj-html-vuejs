<script>
import AppWorkCulture from './AppWorkCulture.vue';
import AppSkills from './AppSkills.vue'


export default {
    name: 'AppMain',

    components: {
        AppWorkCulture,
        AppSkills,
    }

}
</script>
<template>
    <main class="container my_width">
        <AppWorkCulture />

        <AppSkills />






    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>