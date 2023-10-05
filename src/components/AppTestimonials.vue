<script>
export default {
    name: 'AppTestimonials',
}
</script>
<template>
    <section class="testimonials container mt-5 py-5">
        <div class="row align-items-center justify-content-between py-5">
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
            <div class="col-7 py-5 position-relative">
                <!-- top card absolute -->
                <div class="my_testimonials_card abs_card_top p-5">
                    <h5 class="text-black fw-semibold pb-4">
                        The MaxCoach team works really hard to ensure high level of quality
                    </h5>
                    <p class="text-secondary fw-semibold">
                        I am happy with their arrangement of lessons and subjects. They lorem ipsum dolor sit amet
                        consectetur adipisicing elit. Earum, itaque sunt! Quibusdam officiis doloremque veritatis odit ipsa
                        exercitationem explicabo amet!
                    </p>
                    <div class="testimonials_infos d-flex align-items-center pt-4">
                        <img src="../assets/img/testimonial-avata-03.jpg" alt="">
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
                <!-- main card  -->
                <div class="my_testimonials_card p-5">
                    <h5 class="text-black fw-semibold pb-4">
                        Professional team of specialists and passionate mentors at reach
                    </h5>
                    <p class="text-secondary fw-semibold">
                        I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors
                        are smart and professional when dealing with students.
                    </p>
                    <div class="testimonials_infos d-flex align-items-center pt-4">
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
                <!-- bottom card absolute -->
                <div class="my_testimonials_card abs_card_bottom p-5">
                    <h5 class="text-black fw-semibold pb-4">
                        Professional team of specialists and passionate mentors at reach
                    </h5>
                    <p class="text-secondary fw-semibold">
                        I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors
                        are smart and professional when dealing with students.
                    </p>
                    <div class="testimonials_infos d-flex align-items-center pt-4">
                        <img src="../assets/img/testimonial-avata-02.jpg" alt="">
                        <div class="infos_text ps-3">
                            <h6 class="fw-semibold">
                                MINA HOLLACE
                            </h6>
                            <span class="text-secondary">
                                / Freelancer
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

.abs_card_top {
    position: absolute;
    z-index: -1;
    top: -26%;
    transform: scale(0.8);
    opacity: 0.5;
}

.abs_card_bottom {
    position: absolute;
    z-index: -1;
    bottom: -22%;
    transform: scale(0.8);
    opacity: 0.5;
}


.my_testimonials_card {
    background-color: white;
    padding: 2rem;
    box-shadow: 10px 10px 15px rgba($coach-grey, 0.1), -10px -10px 10px rgba($coach-grey, 0.1);
}


.testimonials_infos {

    img {
        width: 90px;
        border-radius: 50%;
    }

}
</style>