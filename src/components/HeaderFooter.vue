<template>
    <div class="head_container container">
        <div class="card_container">
            <figure>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Banner Dc digital">
            </figure>
            <div>
                <p class="text-uppercase text-smaller">Digital Comics</p>
            </div>
        </div>
        <div class="card_container">
            <figure>
                <img src="../assets/img/buy-comics-merchandise.png" alt="Dc Merchandise">
            </figure>
            <div>
                <p class="text-uppercase text-smaller">DC Merchandise</p>
            </div>
        </div>
        <div class="card_container">
            <figure>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Banner Dc digital">
            </figure>
            <div>
                <p class="text-uppercase text-smaller">Subscription</p>
            </div>
        </div>
        <div class="card_container">
            <figure>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Banner Dc digital">
            </figure>
            <div>
                <p class="text-uppercase text-smaller">Comic Shop Locator</p>
            </div>
        </div>
        <div class="card_container">
            <figure>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="Banner Dc digital">
            </figure>
            <div>
                <p class="text-uppercase text-smaller">Dc Power Visa</p>
            </div>
        </div>
    </div>
    
        
</template>

<script>
    export default  {

    }
</script>

<style lang="scss" scoped>
    .head_container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 10px;
        .card_container {
            display: flex;
            align-items: center;
            gap: 10px;
            flex-basis: 0;
            flex-grow: 1;
        }
        figure {
            flex-basis: 20%;
            img {
                width: 45px;
            }
        }
        div {
            flex-basis: 80%;
            p {
                color: white;
            }
        }
       
    }
</style>
        