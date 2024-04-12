<script>
import AppHeader from "./components/AppHeader.vue";
import AppContents from "./components/AppContents.vue";
import AppSection from "./components/AppSection.vue";
import AppFooterTop from "./components/AppFooterTop.vue";

export default{
  components: {
    AppHeader,
    AppContents,
    AppSection,
    AppFooterTop
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
</footer>
  
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;

</style>
