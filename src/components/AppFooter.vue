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
                    colonna
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
            background-image: url('/public/img/');
            > .container {
                .col{
                    width: 20%;
                }
            }
        }
    }
</style>
