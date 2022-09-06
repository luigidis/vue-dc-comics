<template>
    <div class="card">
        <img :src="thumb" :alt="series">
        <h3>{{series}}</h3>
    </div>
</template>

<script>
    export default {
        props: {
            thumb: String,
            series: String,
        }
    }
            
</script>

<style lang="scss" scoped>

.card {
     // padding: 10px;
     display: flex;
     flex-direction: column;
     max-width: 185px;
     img {
         width: 100%;
         aspect-ratio: 1;
         flex-basis: 80%;
    }
     h3 {
         color: white;
         text-transform: uppercase;
         padding-top: 20px;
         font-size: 0.85rem;
    }
}
</style>