<script>
export default {
    name: 'AppJumbotron'
}
</script>
<template>
    <section id="jumbotron" class="jumbotron d-flex align-items-center justify-content-center position-relative">
        <!-- central section -->
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
        <!-- right menu absolute -->
        <div class="right_menu d-flex flex-column align-items-center">
            <a href="#">
                <i class="fa-solid fa-ruler-vertical fa-sm text-black"></i>
            </a>
            <a href="#" class="py-3">
                <i class="fa-solid fa-life-ring fa-sm text-black"></i>
            </a>
            <a href="#" class="pb-3">
                <i class="fa-solid fa-book fa-sm text-black"></i>
            </a>
            <a href="#">
                <i class="fa-solid fa-cart-shopping fa-sm text-black"></i>
            </a>
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

        &:hover {
            background-color: $coach-green;
            color: white;
        }

    }

    .right_menu {
        position: absolute;
        top: 20%;
        right: 0%;
        background-color: white;
        padding: 1.2rem .8rem;
        border-top-left-radius: 5px;
        border-bottom-left-radius: 5px;
    }


}
</style>