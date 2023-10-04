<script>
export default {
    name: 'AppMain'
}
</script>
<template>
    <main class="container my_width">
        <section class="work_culture">
            <div class="row">
                <!-- column left with paragraphs -->
                <div class="col-4 pt-5">
                    <h6 class="my_grey">
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
                <div class="col-6 my_bg_img my_pt position-relative">
                    <img src="../assets/img/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
                </div>
            </div>
        </section>
    </main>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.work_culture {
    margin-top: 8rem;
    margin-bottom: 8rem;

    .my_bg_img {
        background-image: url(../assets/img/maxcoach-shape-07-150x150.png);
        background-repeat: no-repeat;
        background-position: top 0% right 20%;
    }

    .my_pt {
        padding-top: 4rem;
    }

}
</style>