<script>
export default {
    name: 'AppTransformSection'
}
</script>
<template>
    <div class="lines position-relative">

        <!-- lines bg image -->
        <div class="lines_bg"></div>

        <section class="transform container py-5">
            <div class="row align-items-center">
                <!-- image col -->
                <div class="col-7 my_p position-relative">
                    <img src="../assets/img/home-3-team-image.png" alt="">
                    <!-- background elements -->
                    <div class="image_bgs"></div>
                    <!-- splash bg element -->
                    <div class="splash_svg">
                        <img src="../assets/svg/svg-0.svg" alt="">
                    </div>
                </div>
                <!-- text col -->
                <div class="col-4 ms-2 position-relative">

                    <!-- ring bg image -->
                    <div class="ring_bg"></div>

                    <!-- column content -->
                    <h6 class="my_grey pt-5">
                        Everything in <span class="fw-bolder">MAXCOACH</span>
                    </h6>
                    <p class="fs-1 fw-semibold lh-sm">
                        We're Here To <span class="my_green fw-light">Transform</span> You!
                    </p>
                    <p class="my_grey mb-5">
                        As learners, people can enjoy great companionship from MaxCoach mentors and educators. We can help
                        you
                        develop and grow at your best.
                    </p>
                    <button class="btn my_btn_transform fw-semibold">
                        Get Free Guide
                    </button>
                </div>
            </div>
        </section>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.my_p {
    padding-left: 8rem;
}

.my_btn_transform {
    background-color: $coach-green;
    color: white;
    padding: 1rem 3rem;
}

.lines_bg {
    height: 120px;
    aspect-ratio: 1/1;

    background-image: url(../assets/img/maxcoach-shape-01.png);
    background-repeat: no-repeat;
    background-position: top 30% left 10%;
    background-size: contain;

    position: absolute;
    top: 80%;
    left: 6%;

}

.image_bgs {
    height: 700px;
    width: 700px;
    position: absolute;
    left: -10%;
    top: -10%;
    z-index: -1;
    background-image: url(../assets/img/maxcoach-shape-07.png), url(../assets/img/maxcoach-shape-05-150x150.png);
    background-repeat: no-repeat, no-repeat;
    background-position: bottom 10% right 21%, top 38% left 15%;
    background-size: 160px, 180px;
}

.splash_svg {
    position: absolute;
    left: 14%;
    top: 12%;
    z-index: -2;

    img {
        width: 170px;
        filter: invert(62%) sepia(34%) saturate(909%) hue-rotate(120deg) brightness(85%) contrast(85%);
        opacity: .5;
    }

}

.ring_bg {
    height: 70px;
    aspect-ratio: 1/1;
    opacity: .3;

    background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Orange_circle_100%25.svg/200px-Orange_circle_100%25.svg.png);
    background-repeat: no-repeat;
    background-position: top 30% left 10%;
    background-size: contain;

    position: absolute;
    top: -20%;
    left: -10%;
}
</style>