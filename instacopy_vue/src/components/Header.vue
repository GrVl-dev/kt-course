<template>
    <header class="header">
        <div class="header__content">
            <router-link to="/" class="header__logo">
                <img src="@/assets/img/logocopy.png" alt="">
            </router-link>
            <form class="header__search">
                <input class="header__search" type="search" placeholder="Поиск">
            </form>
            <div class="header__menu">
                <router-link to="/">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 25" width="25px" height="25px">
                        <use xlink:href="@/assets/img/sprite.svg#home-enabled"></use>
                    </svg>
                </router-link>
                <router-link to="/direct">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 25" width="25px" height="25px">
                        <use xlink:href="@/assets/img/sprite.svg#msg"></use>
                    </svg>
                </router-link>
                <router-link to="#">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 25" width="25px" height="25px">
                        <use xlink:href="@/assets/img/sprite.svg#explore"></use>
                    </svg>
                </router-link>
                <router-link to="#">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 25" width="25px" height="25px">
                        <use xlink:href="@/assets/img/sprite.svg#heart"></use>
                    </svg>
                </router-link>
                <router-link to="#">
                    <img class="header__menu-profile" src="@/assets/img/users/noName_163/foto.jpg">
                </router-link>
            </div>
            <div class="header__gamb"></div>
        </div>
    </header>
</template>
<script>

export default {
    name: "Header"
};
</script>