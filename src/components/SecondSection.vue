<template>
    <div class="container">
        <section class="second-section">
            <ul class="active-links-second-section">
                <li>1</li>
                <li>1</li>
                <li>1</li>
                <li>1</li>
                <li>1</li>
            </ul>
            <span class="second-section-title">
            current series
            </span>
        </section>
        
    </div>
</template>

<script>
export default {
    name: "FirstSection"
}
</script>

<style scoped>
    .second-section {
        width: 70%;
        font-size: 20px;
        color: white;
        height: 100px;
        position: relative;
        margin: auto;
    }

    .active-links-second-section {
        display: flex;
        justify-content: center;
        align-items: center;
    }


    .container {
        background-color: black;
        
    }

    .second-section-title {
        background-color: #0282f9;
        text-transform: uppercase;
        position: absolute;
        top: -10px;
        left: 0;
        padding: 10px;
    }
</style>