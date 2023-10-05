<script>
export default {
    name: 'AppfooterItem',

    props: {
        item: Object,
    }
}
</script>
<template>
    <div class="col-3 d-flex flex-column " :class="(item.name === null ? 'my_p' : '')">
        <h6 class="text-light fw-semibold">
            {{ item.name }}
        </h6>
        <a v-for="link in  item.links" :href="link.link_url">
            {{ link.link_name }}
        </a>
    </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;

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
</style>