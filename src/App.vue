<script>
import AppHeader from "./components/AppHeader.vue";
import AppContents from "./components/AppContents.vue";
import AppSection from "./components/AppSection.vue";
import AppFooterTop from "./components/AppFooterTop.vue";
import AppFooterBot from "./components/AppFooterBot.vue";
import Cards from "./components/Cards.vue";
import Jumbotron from "./components/Jumbotron.vue";
export default{
  components: {
    AppHeader,
    AppContents,
    AppSection,
    AppFooterTop,
    AppFooterBot,
    Cards,
    Jumbotron,
    }
}
</script>

<template>

<header>
  <AppHeader></AppHeader>
</header>

<main>
  <Jumbotron></Jumbotron>
  <AppContents>
    <Cards></Cards>
  </AppContents>
  <AppSection></AppSection>
</main>

<footer>
  <AppFooterTop></AppFooterTop>
  <AppFooterBot></AppFooterBot>
</footer>
  
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;

</style>
