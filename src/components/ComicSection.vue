<script>
import ComicItem from './ComicItem.vue'
export default {
    name: 'ComicsSection',
    props: {
        comics: Array
    },
    components: {
        ComicItem
    }
}

</script>

<template>
    <section class="comics">

        <div class="container">
            <h3>Current Series</h3>
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3">

                <!-- Comic Item -->
                <ComicItem :comic="comic" v-for="comic in comics"></ComicItem>

            </div>
        </div>

    </section>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
    .comics {
        h3 {
            background-color: $primary;
            margin-top: -2rem;
            margin-bottom: 2rem;
        }
    }

</style>