<template>
    <div class="banner-custom">
        <nuxt-link to="/solusi">
            <img src="https://otomoto-website-laravel.s3.ap-southeast-1.amazonaws.com/cWbWIsQHHD3V1YLvnFgi6Oo5W33k22vByzLlOZbJ.jpeg" alt="">
        </nuxt-link>
    </div>
</template>

<script>
export default {
    name: "BannerCustom"
}
</script>

<style scoped lang="sass">
    .banner-custom
        img
            width: 100%
            height: 370px
            object-fit: cover
</style>