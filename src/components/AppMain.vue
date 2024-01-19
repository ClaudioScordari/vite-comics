<script>
import AppMyCard from "../components/AppMyCard.vue";

export default {
    data(){
        return {
            comics: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book",
                },
                {
                    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel",
                },
                {
                    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel",
                }
            ]
        }
    },
    components: {
        AppMyCard
    },
    methods: {}
}
</script>

<!-- ------------------------------------------------------------------------------- -->

<template>
    <main>
        
        <section>
            <div class="jumbotron">
                <!-- img background -->

                <div>
                    <a href="">
                        CURRENT SERIES
                    </a>
                </div>
            </div>

            <div class="container">

                <div class="all-comics">

                    <AppMyCard v-for="(oneComic, i) in comics" :comic="oneComic"/>

                </div>

                <div class="load_more-button">
                    <a href="">
                        LOAD MORE
                    </a>
                </div>

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

        // General
        img{
            width: 100%;
        }
        .container {
            margin: 0 auto;
            max-width: 1100px;
        }
        //

        > section:nth-of-type(1){
            color: white;
            background-color: #1C1C1C;
            padding-bottom: 50px;

            .jumbotron{
                width: 100%;
                height: 400px;
                background-image: url('/public/img/jumbotron.jpg');
                background-size: 100% auto;
                position: relative;

                a{
                    text-decoration: none;
                    color: white;
                    padding: 20px;
                    background-color: #0282F9;
                    font-size: 20px;
                    position: absolute;
                    bottom: -20px;
                    left: 25%;
                }
            }
            .all-comics{
                padding-top: 50px;
                display: flex;
                flex-wrap: wrap;
                gap: 15px;
            }

            .load_more-button{
                text-align: center;
                margin-top: 30px;
                a{
                    text-decoration: none;
                    color: white;
                    font-size: 20px;
                    background-color: #0282F9;
                    padding: 15px;
                }
            }
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
