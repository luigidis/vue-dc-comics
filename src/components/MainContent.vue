<template>
    <div class="bg-color-black">
       <div class="container">
            <div class="card" v-for="(banner,i) in banners" :key="i">
                <img :src="banner.thumb" :alt=banner.type>
                <h3>{{ banner.series}}</h3>
            </div>
        </div>

    </div>
</template>
<script>
    import banners from '../banners'
    export default {
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
        .card {
            padding: 10px;
            display: flex;
            flex-direction: column;
            img {
                width: 185px;
                aspect-ratio: 1;
                flex-basis: 80%;
            }
            h3 {
                color: white;
                text-transform: uppercase;
            }
        }
            

    }
}
    
</style>