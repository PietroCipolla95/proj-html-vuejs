<script>
export default {
    name: 'AppCourses',
}
</script>
<template>
    <div class="my_bg">
        <section class="courses container">
            <h6 class="text-center my_grey">
                JOIN MAXCOACH AT BEST
            </h6>
            <h1 class="text-center fw-semibold">
                Latest Online <span class="my_green fw-normal">Courses</span>
            </h1>
            <!-- cards row -->
            <div class="row my-5">
                <div class="col-4">
                    <div class="card border-0">
                        <!-- card image -->
                        <img src="../assets/img/course-02-480x298.jpg" alt="">
                        <div class="card-body px-4 pt-4">
                            <!-- price -->
                            <span class="my_green fs-4 fw-bold">
                                $40.<span class="fs-5">00</span>
                            </span>
                            <!-- course type -->
                            <a href="#">
                                <h4 class="fw-semibold py-3">
                                    Learning to Write as a Professional Author
                                </h4>
                            </a>
                            <!-- info about students and lessons -->
                            <div class="card_info d-flex">
                                <div class="">
                                    <i class="fa-regular fa-file-lines"></i>
                                    <span class="ps-2">20 Lessons</span>
                                </div>
                                <div class="ps-4">
                                    <i class="fa-regular fa-user"></i>
                                    <span class="ps-2">50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card border-0">
                        <!-- card image -->
                        <img src="../assets/img/stock-full-hd-03-480x298.jpg" alt="">
                        <div class="card-body px-4 pt-4">
                            <!-- price -->
                            <span class="my_green fs-4 fw-bold">
                                $0.<span class="fs-5">00</span>
                            </span>
                            <!-- course type -->
                            <a href="#">
                                <h4 class="fw-semibold py-3">
                                    Customer-centric Info-Tech Strategies
                                </h4>
                            </a>
                            <!-- info about students and lessons -->
                            <div class="card_info d-flex">
                                <div class="">
                                    <i class="fa-regular fa-file-lines"></i>
                                    <span class="ps-2">24 Lessons</span>
                                </div>
                                <div class="ps-4">
                                    <i class="fa-regular fa-user"></i>
                                    <span class="ps-2">769 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card border-0">
                        <!-- card image -->
                        <img src="../assets/img/stock-full-hd-04-480x298.jpg" alt="">
                        <div class="card-body px-4 pt-4">
                            <!-- price -->
                            <span class="my_green fs-4 fw-bold">
                                $19.<span class="fs-5">00</span>
                            </span>
                            <!-- course type -->
                            <a href="#">
                                <h4 class="fw-semibold py-3">
                                    Open Programming Courses for Everyone: Python
                                </h4>
                            </a>
                            <!-- info about students and lessons -->
                            <div class="card_info d-flex">
                                <div class="">
                                    <i class="fa-regular fa-file-lines"></i>
                                    <span class="ps-2">17 Lessons</span>
                                </div>
                                <div class="ps-4">
                                    <i class="fa-regular fa-user"></i>
                                    <span class="ps-2">62 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- circles -->
            <div class="d-flex justify-content-center align-items-center pb-5">
                <div class="my_circle_active"></div>
                <div class="my_circle"></div>
                <div class="my_circle"></div>
                <div class="my_circle"></div>
                <div class="my_circle"></div>
            </div>
            <!-- paragraph to view all courses available -->
            <div class="d-flex justify-content-center w-50 m-auto">
                <p class="text-center fw-semibold my_grey ">
                    Control your personal preference settings to get notified about appropriate courses.
                    <a href="#" class="text-black link-underline-secondary">
                        View all courses &#8594
                    </a>
                </p>
            </div>

        </section>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.my_bg {
    background: rgb(255, 255, 255);
    background: linear-gradient(180deg, rgba(255, 255, 255, 1) 6%, rgba(245, 241, 237, 1) 44%);
}

h1 {
    font-size: 3rem;
}

.card {

    img {
        border-top-right-radius: 10px;
        border-top-left-radius: 10px;
    }

    .card_info {
        color: $coach-grey;
        font-size: .8rem;
    }

    a {
        text-decoration: none;
    }

    h4 {
        color: black;
    }

    & h4:hover {
        color: $coach-green;
    }
}

.my_circle {
    margin: 0 1rem;
    background-color: $coach-grey;
    height: 10px;
    aspect-ratio: 1/1;
    border-radius: 50%;
    opacity: .5;
}

.my_circle_active {
    margin: 0 1rem;
    background-color: black;
    height: 15px;
    aspect-ratio: 1/1;
    border-radius: 50%;
}
</style>