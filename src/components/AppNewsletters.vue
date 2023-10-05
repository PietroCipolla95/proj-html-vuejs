<script>
export default {
    name: 'AppNewsletters'
}
</script>
<template>
    <div class="newsletters_wrapper position-relative">

        <!-- bgs images newsletters -->

        <div class="image_bgs_newsletters"></div>

        <div class="ring_bgs"></div>

        <section class="newsletters container py-5">
            <div class="row d-flex justify-content-center">
                <div class="col-6">
                    <h1 class="text-center fw-semibold">
                        Subscribe <span class="my_green fw-normal">Newsletters</span>
                    </h1>
                    <h6 class="text-center my_grey">
                        Enter your email adress to register to our newsletter subscription delivered on a regular basis!
                    </h6>
                    <div class="input-group pt-5">
                        <input type="text" class="form-control" placeholder="Enter your email">
                        <button class="btn my_btn_newsletter" type="button">Subscribe</button>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

.my_btn_newsletter {
    background-color: $coach-green;
    height: 55px;
    color: white;
    font-weight: bold;
    font-size: .8rem;
    padding: 0 1.9rem;
}

.image_bgs_newsletters {
    height: 100%;
    aspect-ratio: 1/1;

    background-image: url(../assets/img/maxcoach-shape-02.png), url(../assets/img/maxcoach-shape-09.png);
    background-repeat: no-repeat, no-repeat;
    background-position: top 30% left 10%, top -20% right 150%;
    background-size: 120px, 200px;

    position: absolute;
    top: 25%;
    right: 10%;
}

.ring_bgs {
    position: absolute;
    top: 45%;
    left: 15%;

    width: 80px;
    aspect-ratio: 1/1;
    background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Breezeicons-actions-22-draw-circle.svg/512px-Breezeicons-actions-22-draw-circle.svg.png?20160527121452);
    background-repeat: no-repeat;
    background-size: contain;

    filter: invert(54%) sepia(16%) saturate(1799%) hue-rotate(120deg) brightness(100%) contrast(91%);
    opacity: .5;
}
</style>