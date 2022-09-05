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
                                <h3>ciao</h3>
                            </li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>
                                <h3>ciao</h3>
                            </li>
                            <li>ciao</li>
                            <li>ciao</li>
                        </ul>
                        <ul class="col">
                            <li>
                                <h3>ciao</h3>
                            </li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                        </ul>
                        <ul class="col">
                            <li>
                                <h3>ciao</h3>
                            </li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
                            <li>ciao</li>
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
                            <img src="../assets/img/footer-facebook.png" alt="">
                       </li>
                       <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                       </li>
                       <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                       </li>
                       <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                       </li>
                       <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
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
.big {
    .bg-color-cyan {
        height: 191px;
        background-color: #0282F9;
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
            .icons {
                display: flex;
                align-items: center;
                gap: 20px;
                .text_follow {
                    color: #0282F9;
                    font-weight: bold;
                    text-transform: uppercase;
                }
            }
            
        }
    }

}
</style>