<script>

  export default {
    name: 'SiteMain',
  }

</script>

<template>

    <main>

    <!-- #region content -->
        <section class="bg-black">
        <div class="container m-auto py-4">
            <h2 class="content-here"> -> Content goes here</h2>
        </div>
        </section>
    <!-- #endregion content -->

    <!-- #region buy -->
        <section class="bg-buy">

        <div class="container m-auto d-flex justify-content-around">
            
            <div class="comics d-flex py-4">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <p>DIGITAL COMICS</p>
            </div>

            <div class="comics d-flex py-4">
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
            </div>

        </div>

        </section>
    <!-- #endregion buy -->
    </main>

</template>

<style lang="scss" scoped></style>