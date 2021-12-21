<template>
    <header>
        <div class="container">
            <div class="header-box">
                <div>
                    <img src="../assets/img/dc-logo.png" alt="logo dc comics">
                </div>
                <ul class="nav-bar">
                    <li>CHARACTERS</li>
                    <li class="-blue">COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FAN</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>

    

    .nav-bar {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        height: 66px;
    }

    li {
        padding: 0 10px;
        font-size: 8px;
        font-weight: bold;
      
    }

    *[class$="blue"] {
        border-bottom: 4px solid blue;
        line-height: 63px;
        padding-top: 4px;
    }

    img {
        width: 100%;
        height: 60px;
    }

    
.header-box {
      width: 70%;
      height: 60px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      
    }

    header {
        padding:10px;
    }
   


</style>