<script>
export default {
    name: 'AppWave',
}
</script>
<template>
    <div class="wave_wrap">
        <img src="../assets/svg/svg-1.svg" alt="" class="wave">
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.wave {
    width: 100%;
    background-color: $coach-lightgrey;
}
</style>