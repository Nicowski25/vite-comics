<script>

</script>

<template>
<!-- header section -->
  <header>
    <nav class="navbar">
      <div class="container m-auto py-1">
        <div class="row w-100 justify-content-between align-items-center">

          <div class="col">
            <img src="./assets/img/dc-logo.png" alt="">
          </div>

          <div class="col">
            <ul class="d-flex ls-none">
              <li href="#">CHARACTERS</li>
              <li href="#">COMICS</li>
              <li href="#">MOVIES</li>
              <li href="#">TV</li>
              <li href="#">GAMES</li>
              <li href="#">COLLECTIBLES</li>
              <li href="#">VIDEOS</li>
              <li href="#">FANS</li>
              <li href="#">NEWS</li>
              <li href="#">CHARACTERS</li>
            </ul>
          </div>

        </div>
      </div>
    </nav>
  </header>

  <main>

<!-- #region content -->
    <section class="bg-black">
      <div class="container m-auto py-4">
        <h2 class="content-here"> -> Content goes here</h2>
      </div>
    </section>
<!-- #endregion content -->

    <section class="bg-buy">

      <div class="container m-auto d-flex justify-content-around">
        
        <div class="comics d-flex py-4">
          <img src="./assets/img/buy-comics-digital-comics.png" alt="">
          <p>DIGITAL COMICS</p>
        </div>

        <div class="comics d-flex py-4">
          <img src="./assets/img/buy-comics-merchandise.png" alt="">
          <p>DC MERCHANDISE</p>
        </div>

        <div class="comics d-flex py-4">
          <img src="./assets/img/buy-comics-subscriptions.png" alt="">
          <p>SUBSCRIPTIONS</p>
        </div>

        <div class="comics d-flex py-4">
          <img src="./assets/img/buy-comics-shop-locator.png" alt="">
          <p>COMIC SHOP LOCATOR</p>
        </div>

        <div class="comics d-flex py-4">
          <img src="./assets/img/buy-dc-power-visa.svg" alt="">
          <p>DC POWER VISA</p>
        </div>

      </div>

    </section>
  </main>

  <footer></footer>

</template>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.ls-none {
  list-style: none;
  
  li {
    padding-right: 1rem;
  }
}

.content-here {
  color: white;
}

.bg-buy {
  background-color: #154bb1;
}

.comics {
  align-items: center;
  img {
    height: 60px;
  }
}

</style>
