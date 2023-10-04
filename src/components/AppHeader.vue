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
                        <form class="d-flex" role="search">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        </form>
                    </div>
                </div>
            </div>
        </nav>
    </header>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

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