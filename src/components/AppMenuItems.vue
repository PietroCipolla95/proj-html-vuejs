<script>

import { header_items } from '../header_menu';


export default {
    name: 'AppMenuItems',

    data() {
        return {
            header_items,
        }
    },

}
</script>
<template>
    <li class="nav-item dropdown" v-for="item in  header_items.items ">
        <a class="nav-link dropdown-toggle my_toggle pb-0" href="#" role="button" data-bs-toggle="dropdown"
            aria-expanded="false">
            {{ item.title }}
        </a>
        <ul class="dropdown-menu my_dropdown">
            <li v-for="link in  item.links ">
                <a class="dropdown-item" :href="link.link_url">{{ link.link_name }}</a>
            </li>
        </ul>
    </li>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables.scss' as *;


.dropdown a {
    font-size: 14px;
}

.my_dropdown {
    padding-top: 0;
    padding-bottom: 0;
    top: 164%;
    border-radius: 0;
    border: 0px;
}

.my_toggle {
    border-bottom: 1px solid white;
}

.dropdown-toggle:hover {
    color: $coach-green;
    border-bottom: 1px solid $coach-green;
}

.dropdown-item:hover {
    background-color: $coach-green;
}
</style>