<script>
import JumboTron from './JumboTron.vue';
import ComicsSection from './ComicSection.vue';
import comics from '../assets/dc-comics';
  export default {
    name: 'SiteMain',
    components: {
      JumboTron,
      ComicsSection
  },
  data() {
    return {
      comics
    }
  }
}
</script>

<template>

    <main>
      
      <JumboTron></JumboTron>
      <!-- Comics section -->
      <ComicsSection :comics="comics" ></ComicsSection>


    </main>

</template>

<style lang="scss" scoped></style>