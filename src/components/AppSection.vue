<script>
export default {
    name: "AppSection"
}
</script>

<template>
<div class="container-fluid">
    <div class="row ms-container">
        <div class="col"></div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

.container-fluid{
    background-color: $brand-primary;
}

.ms-container {
    max-width: 1200px;
    margin: auto;
    height: 160px;  
}
</style>