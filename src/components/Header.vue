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
        line-height: 107px;
    }

    img {
        width: 100%;
        height: 100px;
    }

    
.header-box {
      width: 70%;
      height: 100px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      
    }

    header {
        padding:10px;
    }
   


</style>