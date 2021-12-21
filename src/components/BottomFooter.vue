<template>
    <div class="container">
        <div class="bottom-footer-container">
            <div class="left">
                <button>mfimrivnc</button>
            </div>
            <div class="right">
                <span>FOLLOW US</span>
                <ul>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'BottomFooter'
}
</script>

<style scoped>
    .bottom-footer-container {
        height: 100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 70%;
        margin: auto;
        color: white;
    }
    .container {
        background-color: #303030;
        
    }
    .right {
        display: flex;
        justify-content: center;
        align-items: center;
        
    }
    ul {
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 0 10px;
    }

    li{
        padding: 0 10px;
    }
</style>