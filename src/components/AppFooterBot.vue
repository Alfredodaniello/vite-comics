<script>
export default {
    name: "AppFooterBot"
}
</script>

<template>
<div class="container-fluid">
    <div class="row ms-container">
        <div class="col d-flex justify-content-between">
            <div>
                <button type="button" class="btn btn-outline-primary">SIGN-UP NOW</button>
            </div>
            <div>
                <nav>
                    <ul class="d-flex align-items-center gap-3" >
                        <li class="title">FOLLOW US</li>
                        <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;
@use "../style/partials/generic" as *;

.container-fluid{
    min-height: 120px;
    background-color: #303030;
}
.ms-container {
    max-width: 1200px;
    margin: auto;
}

.btn-outline-primary {
    --bs-btn-color: #ffffff;
    --bs-btn-border-color: #0282f9;
    --bs-btn-hover-bg: #0282f9;
}

div {
    line-height: 120px;
}

li{
    color: $brand-primary;
}

</style>