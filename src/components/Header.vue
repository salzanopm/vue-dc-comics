<template>
    <header>
        <div class="header-container">
            <div class="header-box">
                <div>
                    <img src="../assets/img/dc-logo.png" alt="logo dc comics">
                </div>
                <ul class="nav-bar">
                    <li>CHARACTERS</li>
                    <li class="-blue">COMICS</li>
                    <li>MOVIES</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>COMICS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
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

    .header-container {
        height: 90px;
        display: flex;
    }

    .nav-bar {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
    }

    li {
        padding: 0 10px;
        font-size: 10px;
    }

    *[class$="blue"] {
        border-bottom: 4px solid blue;
        line-height: 70px;
    }

    img {
        width: 100%;
    }

    
.header-box {
      width: 70%;
      height: 100px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      
    }


</style>