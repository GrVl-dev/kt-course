<template>
    <aside class="aside__wrapper">
        <div class="aside">
            <div class="aside__profile-card">
                <a href="#">
                    <img class="aside__profile-foto" src="@/assets/img/users/noName_163/foto.jpg">
                </a>
                <div class="aside__profile-name">
                    <p>noName_163</p>
                    <p>Имён Нетов</p>
                </div>
            </div>
            <div class="aside__recommend">
                <div class="aside__title">
                    <p>Рекомендации для Вас</p>
                    <a href="#">Все</a>
                </div>
                <div class="aside__card">
                    <div class="aside__card-user">
                        <img class="aside__card-foto" src="@/assets//img/users/UserName/foto.jpg">
                        <div class="aside__card-info">
                            <div class="aside__card-name">UserName</div>
                            <div class="aside__card-data">Ваш подписчик</div>
                        </div>
                    </div>
                    <a href="#" class="aside__card-subscribe">Подписаться</a>
                </div>
                <div class="aside__card">
                    <div class="aside__card-user">
                        <img class="aside__card-foto" src="@/assets/img/users/User_Name/foto.jpg">
                        <div class="aside__card-info">
                            <div class="aside__card-name">User_Name</div>
                            <div class="aside__card-data">Ваш подписчик</div>
                        </div>
                    </div>
                    <a href="#" class="aside__card-subscribe">Подписаться</a>
                </div>
            </div>
            <footer class="aside__footer">© INSTACOPY FROM ME, 2020</footer>
        </div>
    </aside>
</template>

<script>
export default {
    name: "Aside"
}
</script>