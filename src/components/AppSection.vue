<script>
export default {
    name: "AppSection"
}
</script>

<template>
<div class="container-fluid">
    <div class="row ms-container"> 
        <div class="col d-flex align-items-center justify-content-between">
            <div class="logo-container d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <div class="description">DIGITAL COMICS</div>
            </div>
            <div class="logo-container d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <div class="description">DIGITAL COMICS</div>
            </div>
            <div class="logo-container d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <div class="description">DIGITAL COMICS</div>
            </div>
            <div class="logo-container d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <div class="description">DIGITAL COMICS</div>
            </div>
            <div class="logo-container d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <div class="description">DIGITAL COMICS</div>
            </div>
        </div>
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
.logo-container{
    img {
    height: 60px;
}

.description {
    color: #ffffff;
}

}


</style>