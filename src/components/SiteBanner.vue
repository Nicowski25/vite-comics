<script>

export default {
    name: 'SiteBanner',
    data() {
        return {
            banner: [
                {
                    text: 'DIGITAL COMICS',
                    src: 'buy-comics-digital-comics.png'
                },
                {
                    text: 'MERCHANDISE',
                    src: 'buy-comics-merchandise.png'
                },
                {
                    text: 'SUBSCRIPTIONS',
                    src: 'buy-comics-subscriptions.png'
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    src: 'buy-comics-shop-locator.png'
                },
                {
                    text: 'SC POWER VISA',
                    src: 'buy-dc-power-visa.svg'
                },
            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL (`../assets/img/${name}`, import.meta.url).href
        }
    }
}

</script>

<template>

    <section class="bg-buy">

        <div class="container m-auto d-flex justify-content-around">

            <div v-for="item in banner" class="comics d-flex py-4">
                <img :src="getImageUrl( item.src )" alt="">
                <p> {{ item.text }} </p>
            </div>

<!--             <div class="comics d-flex py-4">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
            </div>

            <div class="comics d-flex py-4">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTIONS</p>
            </div>

            <div class="comics d-flex py-4">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </div>

            <div class="comics d-flex py-4">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </div> -->

        </div>

    </section>

</template>

<style lang="scss" scoped></style>