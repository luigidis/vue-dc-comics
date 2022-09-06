<template>
    <div class="bg-color-black">
       <div class="container">
            <CardComic v-for="(banner,i) in banners" :key="i" 
                :series="banner.series" 
                :thumb="banner.thumb" />
        </div>

    </div>
</template>
<script>
    import banners from '../banners'
    import CardComic from './CardComic.vue'

    export default {
        components: {
            CardComic
        },
        data() {
            return { 
                banners: banners
            }
        },
        mounted() {
             console.log(this.banners)
        },
    }   
</script>

<style lang="scss" scoped>
 .bg-color-black {
    height: 600px;
    background-color: #1C1C1C;
    .container {
        display: grid;
        grid-template-columns: repeat(6,1fr);
        gap: 30px;
        padding: 10px;
        
    }
}
</style>
       
                
            

    