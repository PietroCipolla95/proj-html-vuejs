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


        <section class="upgrade_skills">
            <div class="row top_bg_ring">
                <!-- column with image -->
                <div class="col-7">
                    <img src="../assets/img/stock-full-hd-11-670x450.jpg" alt="">
                </div>
                <!-- column with text -->
                <div class="col-4 position-relative overflow-hidden">
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

                    <!-- bottom half ring, other half in the previous section -->
                    <div class="ring_bg"></div>

                </div>
            </div>
        </section>




    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.upgrade_skills {
    margin-bottom: 8rem;

    .ring_bg {
        height: 50px;
        aspect-ratio: 1/1;
        opacity: 50%;

        background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Orange_circle_100%25.svg/200px-Orange_circle_100%25.svg.png);
        background-repeat: no-repeat;
        background-position: top 30% left 10%;
        background-size: contain;

        position: absolute;
        top: -3%;
    }

}
</style>