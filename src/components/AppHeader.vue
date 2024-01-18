<script>
export default {
    data(){
        return {
            arrayNav: [
                'CHARACTER',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP'
            ]
        }
    },
    methods: {
        
    }
}
</script>

<!-- ------------------------------------------------------------------------------- -->

<template>
    <header>
        
        <div class="container">

            <div>
                <img src="/public/img/dc-logo.png" alt="">
            </div>

            <div>
                <nav>
                    <ul>
                        <li v-for="(elem, i) in arrayNav">
                            <a href="">
                                {{ elem }}
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>

        </div>

    </header>
</template>

<!-- ------------------------------------------------------------------------------- -->

<style lang="scss" scoped>

    header{
        > .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1100px;
            margin: 0 auto;

            img {
                width: 80px;
                height: 80px;
            }

            nav > ul{
                display: flex;
                list-style: none;

                > li{
                    padding-top: 40px;
                    padding-bottom: 40px;

                    > a{
                        text-decoration: none;
                        padding-left: 10px;
                        padding-right: 10px;
                        color: black;
                    }
                }

                > li:nth-child(2){
                    border-bottom: 5px solid blue;
                }
            }
        }
    }

</style>
