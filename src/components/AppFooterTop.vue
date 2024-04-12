<script>
export default {
    name: "AppFooterTop"
}
</script>

<template>
<div class="container-fluid">
    <div class="row ms-container">
        <div class="col">
            <nav class="d-flex text-white gap-4 pt-3">
                <div>
                    <ul>
                        <h4>DC COMICS</h4>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                    </ul>

                    <ul>
                        <h4>SHOP</h4>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                    </ul>


                </div>
                
                <ul>
                    <h4>DC</h4>
                    <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                </ul>
                <ul>
                    <h4>SITE</h4>
                    <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                        <li><a href="">dc comics</a></li>
                </ul>
            </nav>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/variables" as *;
@use "../style/partials/generic" as *;

.container-fluid {
    min-height: 250px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.ms-container {
    max-width: 1200px;
    margin: auto;
}

ul {
    padding-left: 0px;
    a {
        color: $brand-secondary
    }
}
</style>