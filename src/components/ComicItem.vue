<script>
export default {
    name: 'ComicItem',
    props: {
        comic: Object,

    }
}

</script>

<template>

    <div class="col" >
        <div class="comic">
        <img class="img-fluid" :src="comic.thumb" alt="">
        <h5> {{ comic.series }} </h5>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.comic {
    img {
        aspect-ratio: 1;
        object-fit: cover;
    }
}

</style>