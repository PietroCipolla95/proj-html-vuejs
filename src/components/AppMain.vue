<script>
import AppWorkCulture from './AppWorkCulture.vue'


export default {
    name: 'AppMain',

    components: {
        AppWorkCulture,
    }

}
</script>
<template>
    <main class="container my_width">
        <AppWorkCulture />
    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;
</style>