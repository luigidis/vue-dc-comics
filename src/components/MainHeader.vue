<template>
    <div class="container">
        <figure>
            <img src="../assets/img/dc-logo.png" alt="Dc Logo">
        </figure>
        <nav class="navbar">
            <ul class="navbar-container">
                <li class="navbar-item">Characters</li>
                <li class="navbar-item">Comics</li>
                <li class="navbar-item">Movies</li>
                <li class="navbar-item">Tv</li>
                <li class="navbar-item">Games</li>
                <li class="navbar-item">Collectibles</li>
                <li class="navbar-item">Videos</li>
                <li class="navbar-item">Fans</li>
                <li class="navbar-item">News</li>
                <li class="navbar-item">Shop</li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
 .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 0;
    height: 144px;
    .navbar-container {
        display: flex;
        gap: 10px;
        color: #303030;
        font-weight: bold;
        text-transform: uppercase;
        // align-self: stretch;
        // position: relative;
        .navbar-item {
            position: relative;
        }
        .navbar-item::after {
            content: "";
            width: 100%;
            background-color: #0C7CEC;
            position: absolute;
            height: 3px;
            bottom: -72px;
            left: 0;
            right: 0;
            
        }
    }
}
        

        
 
</style>