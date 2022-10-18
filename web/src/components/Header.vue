<script>
export default {
    name: "Header",
}
</script>


<template>
    <section class="header">
        <img src="src/assets/idea.png" alt="logo"/>
        <h1>AgeGuesser</h1>
    </section>
</template>


<style lang="scss">
.header {
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: row;
    width: 100%;
    height: 100px;
    background-color: #EF8A17;

    img {
        width: 100px;
        height: 100px;
    }
    
    h1 {
        color: #16191C;
    }
}
</style>