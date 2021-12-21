<template>
    <div class="container">
        <div class="footer-container">
            <div class="left">
                <ul>
                    DC COMICS
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                </ul>
                <ul>
                    DC COMICS
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                </ul>
                <ul>
                    DC COMICS
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
                </ul>
                
                <ul>
                    DC COMICS
                    <li>1</li>
                    <li>1</li>
                    <li>1</li>
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
        width: 70%;
        margin: auto;
        height: 200px;
        background-image: url('../assets/img/footer-bg.jpg');
        color:white;
    }

    .footer-container {
        display: flex;
        justify-content: space-between;
        height: 100%;
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
        padding: 10px;
    }

    li {
        font-size: 8px;
    }
</style>