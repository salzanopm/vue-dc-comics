<template>
    <div class="container">
        <div class="footer-container">
            <div class="left">
                <ul>
                    DC COMICS
                    <li>Charachters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    SHOP
                    <li>Shop DC</li>
                    <li>Shop DC collectibles</li>
                </ul>
                <ul>
                    DC
                    <li>Term of use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
                
                <ul>
                    DC COMICS
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
            <div class="right">
                <img class="footer-logo" src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    .container {
        
        
        height: 200px;
        background-image: url('../assets/img/footer-bg.jpg');
        color:white;
    }

    .footer-container {
        display: flex;
        justify-content: space-between;
        height: 100%;
        width: 70%;
        margin: auto;
    }
    .left {
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
        height: 100%;
        padding: 20px 0 20px 0;
    }
    .right {
        overflow: hidden;
        height: 100%;
        width: 60%;
        position: relative;
    }
    img {
        height: 300px;
    }

    .footer-logo {
       position: absolute;
       right: 0;
        top: -30px;
    }

    ul {
        padding: 5px 10px;
    }

    li {
        font-size: 9px;
        color: #628181;
    }
</style>