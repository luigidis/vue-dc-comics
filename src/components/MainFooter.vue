<template>
    <div class="big">
        <div class="bg-color-cyan">
            <div class="head container">
                
            </div>
        </div>
        <div class=bg-img-footer>
            <div class="mid container">
                <div class="dc-logo-big">
                    <div class="container-mid">
                        <ul class="col">
                            <li>
                                <h3>Dc Comics</h3>
                            </li>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                            <li>
                                <h3>Shop</h3>
                            </li>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                        <ul class="col">
                            <li>
                                <h3>DC</h3>
                            </li>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Raings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                        <ul class="col">
                            <li>
                                <h3>Sites</h3>
                            </li>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                           
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-color-grey">
            <div class="end container">
                <div class="col button">
                    <a href="#" class="sign-up">Sign-up now!</a>
                </div>
                <div class="col">
                    <ul class="icons">
                        <li>
                            <a href="#" class="text_follow">Follow Us</a>
                        </li>
                       <li>
                            <img src="../assets/img/footer-facebook.png" alt="Facebook Logo">
                       </li>
                       <li>
                            <img src="../assets/img/footer-twitter.png" alt="Twitter Logo">
                       </li>
                       <li>
                            <img src="../assets/img/footer-youtube.png" alt="Youtube Logo">
                       </li>
                       <li>
                            <img src="../assets/img/footer-pinterest.png" alt="Pinterest Logo">
                       </li>
                       <li>
                            <img src="../assets/img/footer-periscope.png" alt="Periscope Logo">
                       </li> 
                    </ul>
                </div>
                    
                
                
            </div>
        </div>
    </div>
        
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
    @import '../styles/variables';
    

    .big {
        .bg-color-cyan {
            height: 191px;
            background-color: $bg-cyan;
        }
            
        .bg-img-footer {
            height: 453px;
            background-image: url(../assets/img/footer-bg.jpg);
            background-position: center;
            background-repeat: no-repeat;
            .mid {
                height: 100%;
                .dc-logo-big {
                    flex-grow: 1;
                    flex-basis: 0;
                    justify-content: flex-start;
                    align-items: center;
                    display: flex;
                    background-image: url(../assets/img/dc-logo-bg.png);
                    background-position: right;
                    background-repeat: no-repeat;
                    height: 100%;
                    .container-mid {
                        flex-basis: 50%;
                        display: flex;
                        justify-content: center;
                        gap: 20px;
                        color: white;
                        .col {
                            li {
                                color: #818080;
                                padding: 5px 0;
                                h3 {
                                    text-transform: uppercase;
                                    padding: 10px 0;
                                    color: white;
                                }
                            }

                        }
                    }
                }
            }
        }
                            
                
        .bg-color-grey {
                height: 132px;
                background-color: #505050;
            .end {
                display: flex;
                justify-content: space-between;
                align-items: center;
                padding: 0 10px;
                height: 100%;
                font-size: 1.25rem;
                .button {
                    border: 3px solid $bg-cyan;
                    text-transform: uppercase;
                    color: white;
                    font-weight: bold;
                    padding: 15px;
                }
                .icons {
                    display: flex;
                    align-items: center;
                    gap: 20px;
                    .text_follow {
                        color: $bg-cyan;
                        font-weight: bold;
                        text-transform: uppercase;
                    }
                }
                
            }
        }

    }
</style>