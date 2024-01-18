<script>
export default {
    data(){
        return {

        }
    },
    methods: {
        
    }
}
</script>

<!-- ------------------------------------------------------------------------------- -->

<template>
    <footer>
        <section>
            <div class="container">
                    
                <div class="col">
                    <h3>
                        DC COMICS
                    </h3>

                    <br>

                    <ul>
                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Comics
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Comics
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>
                    </ul>

                    <br>
                    
                    <h3>
                        SHOP
                    </h3>

                    <br>

                    <ul>
                        <li>
                            <a href="">
                                Shop Dc
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Shop Dc Collectibles
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="col">
                    <h3>
                        DC COMICS
                    </h3>

                    <br>

                    <ul>
                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Comics
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Comics
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>
                    </ul>

                    <br>
                    
                    <h3>
                        SHOP
                    </h3>

                    <br>

                    <ul>
                        <li>
                            <a href="">
                                Shop Dc
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Shop Dc Collectibles
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="col">
                    <h3>
                        DC COMICS
                    </h3>

                    <br>

                    <ul>
                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Comics
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Comics
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Movies
                            </a>
                        </li>
                    </ul>

                    <br>
                    
                    <h3>
                        SHOP
                    </h3>

                    <br>

                    <ul>
                        <li>
                            <a href="">
                                Shop Dc
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Shop Dc Collectibles
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <img src="/public/img/dc-logo-bg.png" alt="">
                </div>
    
            </div>
        </section>

        <section>
            <div class="container">
                
                <div>
                    <a class="sign_up-button" href="">
                        SIGN-UP NOW!
                    </a>
                </div>

                <div>
                    <h3>
                        FOLLOW US
                    </h3>

                    <a href="">
                        <img src="/public/img/footer-facebook.png" alt="">
                    </a>

                    <a href="">
                        <img src="/public/img/footer-periscope.png" alt="">
                    </a>

                    <a href="">
                        <img src="/public/img/footer-pinterest.png" alt="">
                    </a>

                    <a href="">
                        <img src="/public/img/footer-twitter.png" alt="">
                    </a>

                    <a href="">
                        <img src="/public/img/footer-youtube.png" alt="">
                    </a>
                </div>

            </div>
        </section>
    </footer>
</template>

<!-- ------------------------------------------------------------------------------- -->

<style lang="scss" scoped>
    .container{
        margin: 0 auto;
        width: 1100px;
    }

    footer{
        > section:nth-of-type(1){
            background-image: url('/public/img/footer-bg.jpg');
            object-fit: contain;
            > .container {
                display: flex;
                align-items: center;
                > .col{
                    width: 15%;

                    h3{
                        color: white;
                    }

                    ul{
                        list-style: none;

                        li{
                            margin-top: 5px;
                        }

                        a{
                            text-decoration: none;
                            color: grey;
                        }
                    }
                }

                > div:nth-of-type(4){
                    flex-grow: 1;
                    
                    img{
                        width: 400px;
                        height: 400px;
                    }
                }
            }
        }

        > section:nth-of-type(2){
            background-color: #303030;
            .container{
                display: flex;
                justify-content: space-between;
                padding-top: 40px;
                padding-bottom: 40px;

                .sign_up-button{
                    text-decoration: none;
                    color: white;
                    font-size: 25px;
                    border: 4px solid lightblue;
                    padding: 15px;
                }

                > div:nth-of-type(2){
                    display: flex;
                    align-items: center;

                    h3{
                        color: lightblue;
                    }

                    *:nth-child(2n) {
                        margin-left: 18px;
                        margin-right: 18px;
                    }
                }
            }
        }
    }
</style>
