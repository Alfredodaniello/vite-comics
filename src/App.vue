<script>
import AppHeader from "./components/AppHeader.vue";
import AppContents from "./components/AppContents.vue";
export default{
  components: {
    AppHeader,
    AppContents,
  }
}
</script>

<template>

<header>
  <AppHeader></AppHeader>
</header>

<main>
  <AppContents></AppContents>
</main>
  
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;

</style>
