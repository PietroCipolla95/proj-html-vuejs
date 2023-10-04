<script>
export default {
    name: 'AppCourses',
}
</script>
<template>
    <section class="courses">
        <h6 class="text-center my_grey">
            JOIN MAXCOACH AT BEST
        </h6>
        <h1 class="text-center fw-semibold">
            Latest Online <span class="my_green fw-normal">Courses</span>
        </h1>
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
    </section>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

h1 {
    font-size: 3rem;
}

img {
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
}

.card_info {
    color: $coach-grey;
}

.card {

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
</style>