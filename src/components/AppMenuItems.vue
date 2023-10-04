<script>
export default {
    name: 'AppMenuItems',

    data() {
        return {
            items: [
                {
                    title: 'Home',
                    links: [
                        'About',
                        'Link 2',
                        'Link 3'
                    ]
                },
                {
                    title: 'Pages',
                    links: [
                        'About',
                        'Link 2',
                        'Link 3'
                    ]
                },
                {
                    title: 'Courses',
                    links: [
                        'About',
                        'Link 2',
                        'Link 3'
                    ]
                },
                {
                    title: 'Features',
                    links: [
                        'About',
                        'Link 2',
                        'Link 3'
                    ]
                },
                {
                    title: 'Blog',
                    links: [
                        'About',
                        'Link 2',
                        'Link 3'
                    ]
                },
                {
                    title: 'Shop',
                    links: [
                        'About',
                        'Link 2',
                        'Link 3',
                        'Link 4',
                    ]
                },

            ]
        }
    },

}
</script>
<template>
    <li class="nav-item dropdown" v-for="item in items">
        <a class="nav-link dropdown-toggle my_toggle pb-0" href="#" role="button" data-bs-toggle="dropdown"
            aria-expanded="false">
            {{ item.title }}
        </a>
        <ul class="dropdown-menu my_dropdown">
            <li v-for="link in item.links">
                <a class="dropdown-item" href="#">{{ link }}</a>
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
    top: 165%;
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