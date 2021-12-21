<template>
    <div class="container">
        <section class="third-section">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>1</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>1</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>1</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>1</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>1</span>
                </li>
            </ul>
        </section>
    </div>
</template>

<script>
export default {
    name: "ThirdSection"
}
</script>

<style scoped>
    .third-section {
        width: 70%;
        font-size: 20px;
        color: white;
        height: 50px;
        
        margin: auto;
        
        
    }

    ul {
        display: flex;
        justify-content: space-between;
        align-items: center; 
        height: 100%;
    
        
    }

    li {
        height: 100%;
        display: flex;
        align-items: center;
    }

    img {
        height: 100%;
    }


    .container {
        background-color: #0282f9;
        height: 100%;
        padding: 20px;
    }

    .span {

    }

</style>