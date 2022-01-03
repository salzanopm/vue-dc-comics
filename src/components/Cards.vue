<template>
    <div class="comic">
        <div class="img-container">
            <img :src="comicObject.thumb" :alt="comicObject.series">
        </div>
        <h4 class="title-cards">{{comicObject.series}}</h4>
    </div>
</template>

<script>
export default {
    name: 'Cards',
    props: ['comicObject']
}
</script>

<style scoped>
    .comic {
        
       width: calc(100% / 6);

    }
    img {
        width: 100%;
    }

    .img-container {
        height: 100px;
        overflow: hidden;
        margin: 10px;
    }

    .title-cards {
        color: white;
        text-transform: uppercase;
        font-size: 10px;
        text-align: left;
        margin: 10px;
    }
    
</style>