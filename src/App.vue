<script>
import AppHeader from "./components/AppHeader.vue";
import AppContents from "./components/AppContents.vue";
import AppSection from "./components/AppSection.vue";

export default{
  components: {
    AppHeader,
    AppContents,
    AppSection
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
  
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;

</style>
