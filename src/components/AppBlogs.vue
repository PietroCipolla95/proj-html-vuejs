<script>
export default {
    name: 'AppBlogs'
}
</script>
<template>
    <div class="blogs_wrapper">
        <section class="blogs container">
            <h6 class="text-center my_grey">
                READ FOR MORE JOYMENT
            </h6>
            <h1 class="text-center fw-semibold">
                Latest From <span class="my_green fw-normal">Our Blogs</span>
            </h1>
            <!-- cards row -->
            <div class="row py-5">
                <!-- first card -->
                <div class="col-4">
                    <div class="card border-0">
                        <!-- card image -->
                        <img src="../assets/img/artist-blog-03-480x325.jpeg" alt="">
                        <div class="card-body px-4 pt-4">
                            <span class="my_grey fs-5">
                                ARTIST
                            </span>
                            <!-- Blog theme -->
                            <a href="#" class="text-black">
                                <h4 class="fw-semibold py-3">
                                    Learning to Write as a Professional Author
                                </h4>
                            </a>
                            <!-- info about date and views -->
                            <div class="card_info d-flex">
                                <div class="">
                                    <i class="fa-regular fa-calendar fa-sm"></i>
                                    <span class="ps-2">May 15, 2020</span>
                                </div>
                                <div class="ps-4">
                                    <i class="fa-regular fa-eye fa-sm"></i>
                                    <span class="ps-2">688 views</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- second card -->
                <div class="col-4">
                    <div class="card border-0">
                        <!-- card image -->
                        <img src="../assets/img/artist-blog-01-480x325.jpg" alt="">
                        <div class="card-body px-4 pt-4">
                            <span class="my_grey fs-5">
                                ARTIST
                            </span>
                            <!-- Blog theme -->
                            <a href="#" class="text-black">
                                <h4 class="fw-semibold py-3">
                                    Pocket-Sized Notebooks Hold Miniature Paintings
                                </h4>
                            </a>
                            <!-- info about date and views -->
                            <div class="card_info d-flex">
                                <div class="">
                                    <i class="fa-regular fa-calendar fa-sm"></i>
                                    <span class="ps-2">May 15, 2020</span>
                                </div>
                                <div class="ps-4">
                                    <i class="fa-regular fa-eye fa-sm"></i>
                                    <span class="ps-2">603 views</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- third card -->
                <div class="col-4">
                    <div class="card border-0">
                        <!-- card image -->
                        <img src="../assets/img/artist-blog-02-480x325.jpg" alt="">
                        <div class="card-body px-4 pt-4">
                            <span class="my_grey fs-5">
                                ARTIST
                            </span>
                            <!-- Blog theme -->
                            <a href="#" class="text-black">
                                <h4 class="fw-semibold py-3">
                                    Connection Between Self-Portatrits and Identity
                                </h4>
                            </a>
                            <!-- info about date and views -->
                            <div class="card_info d-flex">
                                <div class="">
                                    <i class="fa-regular fa-calendar fa-sm"></i>
                                    <span class="ps-2">May 15, 2020</span>
                                </div>
                                <div class="ps-4">
                                    <i class="fa-regular fa-eye fa-sm"></i>
                                    <span class="ps-2">397 views</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.blogs_wrapper {
    margin: 8rem 0 3rem 0;
    padding: 6rem 0;
    background-color: $coach-lightgrey;
}

.blogs {

    .card {

        img {
            border-top-right-radius: 10px;
            border-top-left-radius: 10px;
        }

        a {
            text-decoration: none;

        }

        & h4:hover {
            color: $coach-green;
        }

        .card_info {
            color: $coach-grey;
            font-size: .8rem;
        }

    }

}
</style>