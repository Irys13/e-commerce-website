<template>
    <div class="navBar">
        <a href="#" class="navbar--left navbar--largeButton navbar--buttonHover">
            <img class="navbar__imageButton navbar--whiteImage" src="../assets/img/craft-house.svg">
            <img class="navbar__imageButton navbar--yellowImage" src="../assets/img/craft-house-yellow.svg">
            <h1 class="pageTitle">Craft<br>House</h1>
        </a>

        <span>
            <a href="#" class="navbar--right navbar--smallButton navbar--buttonHover">
                <img class="navbar__imageButton navbar--whiteImage" src="../assets/img/user.svg">
                <img class="navbar__imageButton navbar--yellowImage" src="../assets/img/user-yellow.svg">
            </a>
            <a href="#" class="navbar--right navbar--smallButton navbar--buttonHover">
                <img class="navbar__imageButton navbar--whiteImage" src="../assets/img/cart.svg">
                <img class="navbar__imageButton navbar--yellowImage" src="../assets/img/cart-yellow.svg">
            </a>
        </span>
    </div>

</template>
<style lang="scss">
@import "assets/scss/styles.scss";

    .navBar {
        align-items: center;
        border-bottom: 1px solid $yellow;
        display: flex;
        justify-content: space-between;
        padding: 10px;
        position: relative;
        width: 100%;
    }

    .navBar__craftImage {
        height: 30px;
        left: 20px;
        position: absolute;
        top: 25px;
        width: auto;
        z-index: 1;
    }
    
    .navbar__imageButton {
        height: 100%;
        width: auto;
    }

    .navbar--largeButton {
        display: inline-block;
        height: 50px;
    }

    .navbar--smallButton {
        display: inline-block;
        height: 30px;
        margin-left: 20px;
    }

    .pageTitle {
        display: inline-block;
        font-family: 'Amaranth', sans-serif;
        font-size: 26px;
        margin-left: 5px;
    }

    .navbar--buttonHover {
        .navbar--whiteImage {
            display: inline-block;
        }

        .navbar--yellowImage {
            display: none;
        }
    }

    .navbar--buttonHover:hover {
         .navbar--whiteImage {
            display: none;
        }

        .navbar--yellowImage {
            display: inline-block;
        }
    }
</style>
<script>
export default {

}
</script>