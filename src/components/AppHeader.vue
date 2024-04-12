<script>
export default {
    name: "AppHeader"
}
</script>

<template>
<div class="container">
    <div class="row ms-container d-flex align-items-center">
        <div class="col d-flex justify-content-between align-items-center">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="nav">
                <ul class="d-flex gap-4">
                    <li><a href="">CARACHTERS</a></li>
                    <li class="active"><a href="">COMICS</a></li>
                    <li><a href="">MOVIES</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">GAMES</a></li>
                    <li><a href="">COLLECTABLES</a></li>
                    <li><a href="">VIDEO</a></li>
                    <li><a href="">FANS</a></li>
                    <li><a href="">NEW</a></li>
                    <li><a href="">SHOP</a></li>
                </ul>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;

.ms-container {
    max-width: 1200px;
    margin: auto;
    height: 120px;

}
a {
    text-decoration: none;
    color: $brand-secondary;
}
nav {
    height: 100%;
}
ul {
    margin-bottom: 0;
}
</style>