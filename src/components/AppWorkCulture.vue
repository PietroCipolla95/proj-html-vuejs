<script>
export default {
    name: 'AppWorkCulture'
}
</script>
<template>
    <section class="work_culture">
        <!-- top row -->
        <div class="row">
            <!-- column left with paragraphs -->
            <div class="col-4 pt-5">
                <h6 class="my_grey pt-5">
                    Everything in <span class="fw-bolder">MAXCOACH</span>
                </h6>
                <p class="fs-1 fw-semibold lh-sm">
                    Learn about our <span class="my_green fw-light">Work Culture</span> at MaxCoach
                </p>
                <p class="my_grey mb-5">
                    Spend some time to visit our website or head office and dicscover our current courses, enrollment
                    procedure and registration deadline. We're opening now classes every beginning of each month.
                </p>
                <p class="my_grey">
                    Have questions?
                    <a href="#" class="my_green fw-bold link-underline-secondary">
                        Get Free Guide &#8594
                    </a>
                </p>
            </div>
            <!-- orange ring column -->
            <div class="col-2">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Orange_circle_100%25.svg/200px-Orange_circle_100%25.svg.png"
                    alt="" class="w-50 opacity-50">
            </div>
            <!-- right column images-->
            <div class="col-6 my_bg_img pt-5 position-relative">
                <!-- main image -->
                <div class="pt-5">
                    <img src="../assets/img/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
                </div>
                <!-- top right image  -->
                <div class="image_abs">
                    <img src="../assets/img/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt=""
                        class="rounded-3">
                </div>
                <!-- bottom circle absolute -->
                <div class="circle_abs">
                    <img src="../assets/img/maxcoach-shape-02.png" alt="">
                </div>
            </div>
        </div>



        <!-- bottom row -->
        <div class="row justify-content-center my_mt ">
            <div class="col-3 text-center">
                <h2 class="my_green fw-bold">
                    129+
                </h2>
                <p class="my_grey fw-semibold">
                    ENROLLED LEARNERS
                </p>
            </div>
            <div class="col-3 text-center">
                <h2 class="my_green fw-bold">
                    80
                </h2>
                <p class="my_grey fw-semibold">
                    FINISHED SESSIONS
                </p>
            </div>
            <div class="col-3 text-center">
                <h2 class="my_green fw-bold">
                    4%
                </h2>
                <p class="my_grey fw-semibold">
                    SATISFACTION RATE
                </p>
            </div>
        </div>

    </section>

    <!-- top half ring, other half on section upgrade skills comp -->
    <div id="top_half_ring">
        <div class="ring_bg"></div>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.work_culture {
    margin-top: 5rem;
    padding-bottom: 8rem;

    /* top row */
    .my_bg_img {
        background-image: url(../assets/img/maxcoach-shape-07-150x150.png);
        background-repeat: no-repeat;
        background-position: top 0% right 20%;
    }

    .image_abs {
        position: absolute;
        top: - 5%;
        right: 0;
    }

    .circle_abs {
        position: absolute;
        bottom: - 15%;
        right: 20%;
    }

    /* bottom row */

    .my_mt {
        margin-top: 8rem;
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
        top: 98%;
        left: 58.5%;
    }

}

#top_half_ring {
    height: 30px;
    position: relative;
    overflow: hidden;

    .ring_bg {
        height: 50px;
        aspect-ratio: 1/1;
        opacity: 50%;

        background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Orange_circle_100%25.svg/200px-Orange_circle_100%25.svg.png);
        background-repeat: no-repeat;
        background-position: top 30% left 10%;
        background-size: contain;

        position: absolute;
        top: 40%;
        left: 61%;
    }
}
</style>