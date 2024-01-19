<script>
export default {
    data(){
        return {
           
        }
    },
    props:{
        comic: Object
    },
    methods: {
        
    }
}
</script>

<!-- ------------------------------------------------------------------------------- -->

<template>
    <div class="one-comic">
        <div class="img-comic">
            <img :src="comic.thumb" :alt="comic.series">
        </div>

        <br>

        <div>
            {{ comic.series }}
        </div>
    </div>
</template>

<!-- ------------------------------------------------------------------------------- -->

<style lang="scss" scoped>

img{
    width: 100%;
    height: 280px;
    display: block;
}
.one-comic{
    width: calc((100% / 6) - 15px);
    margin-bottom: 20px;
}
</style>
