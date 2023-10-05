<script>

import AppMenuItems from './AppMenuItems.vue';


export default {
    name: 'AppHeader',

    components: {
        AppMenuItems,
    },

    data() {
        return {

        }
    }


}
</script>
<template>
    <header>
        <nav class="navbar navbar-expand-lg py-3">
            <div class="my_container">
                <div class="collapse navbar-collapse d-flex justify-content-between" id="navbarSupportedContent">
                    <!-- dropdown ul wrapper -->
                    <div class="col-4">
                        <ul class="navbar-nav mb-2 mb-lg-0 col-4">
                            <!-- dropdowns -->
                            <AppMenuItems />
                        </ul>
                    </div>
                    <!-- navbar logo -->
                    <a class="navbar-brand text-center" href="#">
                        <img src="../assets/img/dark-logo.png" alt="" class="w-50">
                    </a>
                    <!-- searchbar cart and user -->
                    <div class="col-4 d-flex justify-content-end align-items-center">
                        <!-- shopping cart -->
                        <div class="cart position-relative">
                            <a href="#">
                                <i class="fa-solid fa-cart-shopping fa-lg text-black"></i>
                            </a>
                            <!-- counter shopping cart -->
                            <div>
                                0
                            </div>
                        </div>
                        <!-- user icon -->
                        <div class="ms-4 me-3">
                            <a href="#">
                                <i class="fa-regular fa-circle-user fa-lg text-black"></i>
                            </a>
                        </div>
                        <form class="d-flex position-relative" role="search">
                            <input class="form-control my_search" type="search" placeholder="Search.." aria-label="Search">

                            <!-- magn glass inside search form -->
                            <div class="glass">
                                <i class="fa-solid fa-magnifying-glass"></i>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </nav>
    </header>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration,
input[type="search"]::-webkit-search-results-button,
input[type="search"]::-webkit-search-results-decoration {
    display: none;
}

.my_search {
    background-color: $coach-white-3;
    border: 0;
    height: 45px;
}

.glass {
    position: absolute;
    right: 5%;
    bottom: 25%;
    color: $coach-green;
}

.cart div {
    color: white;
    font-size: 13px;
    background-color: $coach-green;
    border-radius: 50%;
    height: 1.2rem;
    aspect-ratio: 1/1;
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    top: -50%;
    left: 80%;
}
</style>