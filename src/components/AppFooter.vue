<script>

import { footer_items } from "../footer_menu";

export default {
    name: 'AppFooter',

    data() {
        return {
            footer_items,
        }
    },
}
</script>
<template>
    <footer class="mt-5 position-relative">

        <!-- go up button -->
        <a href="#">
            <button class="btn go_up_btn">
                <span class="fs-3 text-light">
                    &#8593;
                </span>
            </button>
        </a>

        <div class="container">
            <!-- colums wrapper -->
            <div class="row py-5">
                <!-- adress colum -->
                <div class="col-6 d-flex flex-column">
                    <h6 class="text-light fw-semibold">
                        Address
                    </h6>
                    <!-- street adress -->
                    <span>
                        382 NE 191St # 87394 Miami, FL 33179-3899
                    </span>
                    <!-- telephone and available hours -->
                    <span>
                        +1(305) 547-9909(9am - 5pm EST, Monday - Friday)
                    </span>
                    <!-- support email -->
                    <span>
                        support@maxcoach.com
                    </span>
                    <!-- social media wrapper -->
                    <div class="media_wrapper">
                        <!-- facebook -->
                        <a href="#">
                            <i class="fa-brands fa-2xl fa-square-facebook"></i>
                        </a>
                        <!-- twitter -->
                        <a href="#">
                            <i class="fa-brands fa-2xl fa-twitter"></i>
                        </a>
                        <!-- instagram -->
                        <a href="#">
                            <i class="fa-brands fa-2xl fa-instagram"></i>
                        </a>
                        <!-- linkedin -->
                        <a href="#">
                            <i class="fa-brands fa-2xl fa-linkedin"></i>
                        </a>
                    </div>
                </div>
                <!-- menu items column -->
                <div class="col-6">
                    <div class="row">
                        <!-- col -->
                        <div class="col-3 d-flex flex-column " v-for="item in  footer_items.items"
                            :class="(item.name === null ? 'my_p' : '')">
                            <h6 class="text-light fw-semibold">
                                {{ item.name }}
                            </h6>
                            <a v-for="link in  item.links" :href="link.link_url">
                                {{ link.link_name }}
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- copyright -->
            <div class="row pb-4">
                <span class="text-center">
                    © 2020 Maxcoach. All Rights Reserveed
                </span>
            </div>
        </div>
    </footer>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

footer {
    background-color: $coach-footer;

    .my_p {
        padding-top: 1.2rem;
    }

    .go_up_btn {
        position: absolute;
        bottom: 5%;
        right: 2%;
        background-color: $coach-green;
        color: white;
        border-radius: 50%;
        height: 60px;
        aspect-ratio: 1/1;
    }


    span {
        color: $coach-grey;
        font-size: .8rem;
        font-weight: bold;
        padding: .5rem 0;
    }

    i {
        color: $coach-grey;
        padding-right: 2rem;
        padding-top: 2.5rem;

        &:hover {
            color: #328f68;
        }
    }

    a {
        text-decoration: none;
        color: $coach-grey;
        font-size: .8rem;
        font-weight: 600;
        padding: .5rem 0;

        &:hover {
            color: #328f68;
        }

    }
}
</style>