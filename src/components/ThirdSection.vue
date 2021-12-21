<template>
    <div class="container">
        <section class="third-section">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
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
        font-size: 10px;
        padding: 8px;

    }

    img {
        height: 100%;
        margin-right: 5px;
    }


    .container {
        background-color: #0282f9;
        height: 100%;
        padding: 20px;
    }

    .span {

    }

</style>