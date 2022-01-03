<template>
    <div class="container">
        <section class="second-section">
            <span class="second-section-title">
            current series
            </span>
            <div class="comic-list" >
                <Cards v-for="(comic, index) in comics" :key="index" :comicObject="comic" />
            </div>
            <button>Load More</button>
        </section>  
    </div>
</template>

<script>
import Cards from "./Cards.vue";
import ComicJson from "../assets/dc-comics.json";
export default {
    name: "SecondSection",
    components: {
            Cards,
    },
    data: function() {
        return {
            comics: ComicJson
        }
    },
}
</script>

<style scoped>
    .second-section {
        width: 70%;
        font-size: 20px;
        color: white;
        height: 100%;
        position: relative;
        margin: auto;
        text-align: center;
       
    }

    .comic-list {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        
    }

    .active-links-second-section {
        display: flex;
        justify-content: center;
        align-items: center;
    }


    .container {
        background-color: black;
        padding: 50px 0;
    }

    .second-section-title {
        background-color: #0282f9;
        text-transform: uppercase;
        position: absolute;
        top: -70px;
        left: 0;
        padding: 10px;
    }

    button {
       background-color: #0282f9;
       border: none;
       padding: 5px 40px;
       text-transform: uppercase;
       font-size: 10px;
       color: white;
    }
</style>