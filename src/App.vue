<script>
import AppHeader from "./components/AppHeader.vue";
import AppContents from "./components/AppContents.vue";
import AppSection from "./components/AppSection.vue";
import AppFooterTop from "./components/AppFooterTop.vue";
import AppFooterBot from "./components/AppFooterBot.vue";
export default{
  components: {
    AppHeader,
    AppContents,
    AppSection,
    AppFooterTop,
    AppFooterBot
  }
}
</script>

<template>

<header>
  <AppHeader></AppHeader>
</header>

<main>
  <AppContents></AppContents>
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
