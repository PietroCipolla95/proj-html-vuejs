<script>
export default {
    name: 'AppJumbotron'
}
</script>
<template>
    <section class="jumbotron d-flex align-items-center justify-content-center">
        <div class="text-center">
            <h3 class="text-light">
                Commence Business
            </h3>
            <h1 class="mt-2 mb-5 text-light">
                Distant Mentoring Program
            </h1>
            <button class="btn my_btn fw-bolder px-5 py-3">
                Download free guidebook &#8594
            </button>
        </div>
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.jumbotron {
    height: 700px;
    background-repeat: no-repeat;
    background-size: contain;
    background-image: url(../assets/img/home-3-hero-bg.jpg);

    h1 {
        font-size: 50px;
    }

    .my_btn {
        background-color: white;
        color: $coach-green;
    }


}
</style>