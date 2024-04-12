<script>
export default {
    name: "AppContents"
}
</script>

<template>
<div class="container-fluid">
    <div class="row ms-container">
        <div class="col">
            <h1>CONTENTS HERE</h1>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

.container-fluid {
    background-color: $brand-tertiary;
}
.ms-container {
    max-width: 1200px;
    margin: auto;
    height: 120px;
}

h1 {
    color: white;
    line-height: 120px;
}
</style>