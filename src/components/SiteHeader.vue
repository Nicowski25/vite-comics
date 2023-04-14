<script>

  export default {
    name: 'SiteHeader',
    data() {
      return {
        menu: [
          {
            text: 'CHARACTERS',
            href: '#',
            current_page: true,
          },
          {
            text: 'COMICS',
            href: '#',
            current_page: false,
          },
          {
            text: 'MOVIES',
            href: '#',
            current_page: false,
          },
          {
            text: 'TV',
            href: '#',
            current_page: false,
          },
          {
            text: 'GAMES',
            href: '#',
            current_page: false,
          },
          {
            text: 'COLLECTIBLES',
            href: '#',
            current_page: false,
          },
          {
            text: 'VIDEOS',
            href: '#',
            current_page: false,
          },
          {
            text: 'FANS',
            href: '#',
            current_page: false,
          },
          {
            text: 'NEWS',
            href: '#',
            current_page: false,
          },
          {
            text: 'SHOP',
            href: '#',
            current_page: false,
          },
        ]
      }
    }
  };

</script>

<template>

<header>
    <nav class="navbar">
      <div class="container m-auto py-1">
        <div class="row w-100 justify-content-between align-items-center">

          <div class="col">
            <img src="../assets/img/dc-logo.png" alt="">
          </div>

          <div class="col">
            <ul class="d-flex ls-none m-0">
              <li href="#" v-for="item in menu"> {{ item.text }} </li>
            </ul>
          </div>

        </div>
      </div>
    </nav>

  </header>

</template>

<style lang="scss" scoped>

</style>