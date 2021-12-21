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
        
        font-size: 20px;
        color: white;
        height: 100px;
    }

    .active-links-second-section {
        display: flex;
        justify-content: center;
        align-items: center;
    }


    .container {
        background-color: #0282f9;
    }
</style>