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
    <main>
        
        <section>
            <div class="container">
                sezione 1
            </div>
        </section>

        <section>
            <div class="container">
                
                <nav>
                    <ul>
                        <li>
                            <div>
                                <img src="/public/img/buy-comics-digital-comics.png" alt="">
                            </div>

                            <div>
                                DIGITAL COMICS
                            </div>
                        </li>

                        <li>
                            <div>
                                <img src="/public/img/buy-comics-digital-comics.png" alt="">
                            </div>

                            <div>
                                DIGITAL COMICS
                            </div>
                        </li>

                        <li>
                            <div>
                                <img src="/public/img/buy-comics-digital-comics.png" alt="">
                            </div>

                            <div>
                                DIGITAL COMICS
                            </div>
                        </li>

                        <li>
                            <div>
                                <img src="/public/img/buy-comics-digital-comics.png" alt="">
                            </div>

                            <div>
                                DIGITAL COMICS
                            </div>
                        </li>

                        <li>
                            <div>
                                <img src="/public/img/buy-comics-digital-comics.png" alt="">
                            </div>

                            <div>
                                DIGITAL COMICS
                            </div>
                        </li>
                    </ul>
                </nav>

            </div>
        </section>

    </main>
</template>

<!-- ------------------------------------------------------------------------------- -->

<style lang="scss" scoped>

    main {
        .container {
            margin: 0 auto;
            max-width: 1100px;
        }

        > section:nth-of-type(1){
            color: white;
            background-color: #1C1C1C;
            padding-top: 50px;
            padding-bottom: 50px;
        }

        > section:nth-of-type(2){
            color: white;
            background-color: blue;
            padding-top: 50px;
            padding-bottom: 50px;

            .container{
                width: 1000px;
            }

            nav > ul{
                display: flex;
                list-style: none;

                > li {
                    display: flex;
                    align-items: center;

                    > div:nth-child(1){

                        img{
                            width: 50px;
                            height: 60px;
                        }
                    }

                    > div:nth-child(2){
                        padding-left: 10px;
                    }
                }

                > li:nth-child(2n){
                    margin-left: 25px;
                    margin-right: 25px;
                }
            }
        }
    }
</style>
