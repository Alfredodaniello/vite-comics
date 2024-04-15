<script>
export default {
    name: "Cards",
    props: ["info"]
}
</script>

<template>
<div class="div px-2 pb-2 mb-5">
    <img :src="info.thumb" alt="">
    <h5>{{ info.series }}</h5>
</div>
</template>

<style scoped lang="scss">
div {
    width: 16.6%;
    height: 180px;
    img {
        margin-top: 30px;
        width: 100%;
        height: 100%;
    }
    h5 {
        margin-top: 10px;
        color: white;
    }
}
</style>