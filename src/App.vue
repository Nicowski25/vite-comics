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

<!-- #region buy -->
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
<!-- #endregion buy -->
  </main>

  <footer>

<!-- #region footertop -->
    <div class="footertop py-4">

      <div class="text-light container m-auto">
        <div class="row h-100">
        <div class="col-2">
          
          <ul class="ls-none">
            <li>DC COMICS</li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>

          <ul class="ls-none">
            <li>SHOP</li>
            <li>Shop Dc</li>
            <li>Shop Dc Collectibles</li>
          </ul>

        </div>

        <div class="col-2">
          <ul class="ls-none">
            <li>DC</li>
            <li>Terms Of Use</li>
            <li>Privacy policy</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Worksghops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>

        <div class="col-2">
          <ul class="ls-none">
            <li>SITES</li>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>

        <div class="col-6">
          <img src="./assets/img/dc-logo-bg.png" alt="" class="logo-behind">
        </div>

      </div>
    </div>
  </div>
<!-- #endregion footertop -->

<!-- #region footerbottom -->

  <div class="footerbottom py-4">

    <div class="container m-auto">
      <div class="row justify-content-between align-items-center">
        <div class="col">
          <button class="signup-btn">SIGN-UP NOW!</button>
        </div>
        <div class="col d-flex align-items-center justify-content-end">
          <h3 class="px-4 followus">FOLLOW US</h3>
          <ul class="ls-none d-flex">
            <li>
              <img src="./assets/img/footer-facebook.png" alt="">
            </li>
            <li>
              <img src="./assets/img/footer-twitter.png" alt="">
            </li>
            <li>
              <img src="./assets/img/footer-youtube.png" alt="">
            </li>
            <li>
              <img src="./assets/img/footer-pinterest.png" alt="">
            </li>
            <li>
              <img src="./assets/img/footer-periscope.png" alt="">
            </li>
          </ul>
        </div>
      </div>
    </div>

  </div>

<!-- #endregion footerbottom -->
  </footer>

</template>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
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
  position: relative;
  z-index: 1;
}

.comics {
  align-items: center;
  img {
    height: 60px;
  }
  
  p {
    padding-left: 0.6rem;
  }
}

.footertop {
  background-image: url('./assets/img/footer-bg.jpg');
  background-repeat: no-repeat;
  position: relative;
}

.logo-behind {
  position: absolute;
  width: 450px;
  top: -40px;
}

.footerbottom {
  background-color: #303030;
  position: relative;
  z-index: 1;
}

.signup-btn {
  color: white;
  background-color: #303030;
  padding: 0.5rem 1rem;
  border: 2px solid #154bb1;
}

.followus {
  font-weight: 700;
  font-size: 1.5rem;
  color: #154bb1;
}

</style>
