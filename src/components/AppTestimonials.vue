<script>
export default {
    name: 'AppTestimonials',
}
</script>
<template>
    <section class="testimonials container py-5">
        <div class="row align-items-center justify-content-between">
            <!-- left col with texts -->
            <div class="col-4">
                <h6 class="my_grey pt-5">
                    TESTIMONIALS
                </h6>
                <p class="fs-1 fw-semibold lh-sm">
                    Why Do People <span class="my_green fw-light">*Hearts*</span> Us?
                </p>
                <p class="my_grey mb-5">
                    Seeking for verbals of ourservice quality? Find them here. Everything is transparent and straightforward
                    for your sense of justification.
                </p>
                <p class="my_grey">
                    <a href="#" class="text-black fw-bold link-underline-secondary">
                        View all &#8594
                    </a>
                </p>
            </div>
            <!-- right col with cards -->
            <div class="col-7">
                <div class="my_testimonials_card">
                    <h6 class="text-black fw-semibold">
                        Professional team of specialists and passionate mentors at reach
                    </h6>
                    <p class="text-secondary fw-semibold">
                        I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors
                        are smart and professional when dealing with students.
                    </p>
                    <div class="testimonials_infos d-flex align-items-center">
                        <img src="../assets/img/testimonial-avata-01.jpg" alt="">
                        <div class="infos_text ps-3">
                            <h6 class="fw-semibold">
                                MADLEY PONDOR
                            </h6>
                            <span class="text-secondary">
                                / IT Specialist
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.my_testimonials_card {
    padding: 2rem;
    box-shadow: 5px 10px 5px 10px rgba(126, 122, 122, 0.253);
}


.testimonials_infos {

    img {
        width: 90px;
        border-radius: 50%;
    }

}
</style>