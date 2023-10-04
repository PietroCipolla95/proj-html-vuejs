<script>
export default {
    name: 'AppSkills'
}
</script>
<template>
    <section class="upgrade_skills">
        <div class="row top_bg_ring">
            <!-- column with image -->
            <div class="col-7 position-relative">
                <img src="../assets/img/stock-full-hd-11-670x450.jpg" alt="">
                <!-- background elements -->
                <div class="image_bgs"></div>
                <!-- splash bg element -->
                <div class="splash_svg">
                    <img src="../assets/svg/svg-0.svg" alt="">
                </div>
                <!-- youtube icon -->
                <div class="youtube_icon">
                    <img src="../assets/img/icon-youtube-play.png" alt="">
                </div>
            </div>
            <!-- column with text -->
            <div class="col-4 ms-4 position-relative overflow-hidden">
                <h6 class="my_grey pt-5">
                    HOW WE WORK
                </h6>
                <p class="fs-1 fw-semibold lh-sm">
                    Upgrade Your Skills <span class="my_green fw-light">Upgrade Your Life</span>
                </p>
                <p class="my_grey mb-5">
                    Opening up more opportunities in front of you to get the ticket to more enjoyable door in life.
                    Getting equipped with new skills for new sets of insights into your career.
                    MaxCoach accompany learners in every stage of learning.
                </p>
                <p class="my_grey">
                    <a href="#" class="text-black fw-bold link-underline-secondary">
                        Download free guidebook &#8594
                    </a>
                </p>


                <!-- bottom half ring, other half in appWorkculture comp -->
                <div class="ring_bg"></div>
            </div>

        </div>
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.upgrade_skills {

    margin-bottom: 10rem;

    .image_bgs {
        height: 700px;
        width: 900px;
        position: absolute;
        left: -10%;
        top: -10%;
        z-index: -1;
        background-image: url(../assets/img/maxcoach-shape-07.png), url(../assets/img/maxcoach-shape-05-150x150.png);
        background-repeat: no-repeat, no-repeat;
        background-position: bottom 20% right 17%, top 15% left 1%;
        background-size: 150px, 150px;
    }

    .splash_svg {
        position: absolute;
        left: -4%;
        top: -12%;
        z-index: -2;
        color: aqua;

        img {
            width: 120px;
            filter: invert(56%) sepia(29%) saturate(223%) hue-rotate(207deg) brightness(94%) contrast(83%);
            opacity: .2;
        }

    }

    .youtube_icon {
        position: absolute;
        top: 50%;
        right: 40%;
        transform: translate(-50%, -50%);
    }


    .ring_bg {
        height: 50px;
        aspect-ratio: 1/1;
        opacity: 50%;

        background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Orange_circle_100%25.svg/200px-Orange_circle_100%25.svg.png);
        background-repeat: no-repeat;
        background-position: top 30% left 10%;
        background-size: contain;

        position: absolute;
        top: -5%;
        left: 4%;
    }

}
</style>