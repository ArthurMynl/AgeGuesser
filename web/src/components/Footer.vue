<script>
export default {
    name: "Footer",
}
</script>


<template>
    <footer>
        <h4>© Arthur Meyniel 2022 - All rights reserved.</h4>
        <div class="icons">
            <a href="https://www.linkedin.com/in/arthurmeyniel/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://github.com/ArthurMynl" target="blank"><i class="fa-brands fa-square-github"></i></a>
        </div>
    </footer>
</template>


<style lang="scss">
footer {
    margin-top: 48px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 20px 64px;
    gap: 10px;
    background-color: #16191C;


    .icons {
        display: flex;
        flex-direction: row;
        align-items: center;
        padding: 0px;
        gap: 32px;

        a {
            color: #EF8A17;

            i {
                font-size: 2rem;
            }

        }
    }

    h4 {
        color: #EF8A17;
    }

}
</style>