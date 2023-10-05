<script>
export default {
    name: 'AppTransformSection'
}
</script>
<template>
    <section class="transform container py-5">
        <div class="row">
            <!-- image col -->
            <div class="col-6">

            </div>
            <!-- text col -->
            <div class="col-4">
                <h6 class="my_grey pt-5">
                    Everything in <span class="fw-bolder">MAXCOACH</span>
                </h6>
                <p class="fs-1 fw-semibold lh-sm">
                    We're Here To <span class="my_green fw-light">Transform</span> You!
                </p>
                <p class="my_grey mb-5">
                    As learners, people can enjoy great companionship from MaxCoach mentors and educators. We can help you
                    develop and grow at your best.
                </p>
                <button class="btn my_btn_transform fw-semibold">
                    Get Free Guide
                </button>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.my_btn_transform {
    background-color: $coach-green;
    color: white;
    padding: 1rem 3rem;

}
</style>