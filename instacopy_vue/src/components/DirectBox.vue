<template>
        <section class="direct-box">
            <div class="direct-users-header">
                <h1>Direct</h1>
            </div>
            <div class="direct-users-list">
                <div class="direct__card-user">
                    <img class="direct__card-foto" src="@/assets/img/users/UserName/foto.jpg">
                    <div class="direct__card-info">
                        <div class="direct__card-name">UserName</div>
                    </div>
                </div>
                <div class="direct__card-user">
                    <img class="direct__card-foto" src="@/assets/img/users/User_Name/foto.jpg">
                    <div class="direct__card-name">User_Name</div>
                </div>
            </div>
            <div class="direct-msg-header">
                <div class="direct__msg-user">
                    <img class="direct__msg-foto" src="@/assets/img/users/UserName/foto.jpg">
                    <div class="direct__msg-name">UserName</div>
                </div>
            </div>
            <div class="direct-msg-content">
                <div class="direct-msg-my">                        
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut 
                    labore et dolore magna aliqua.
                </div>
                <div class="direct-msg-my">Привет</div>
                <div class="direct-msg-other">
                    <img src="@/assets/img/users/UserName/foto.jpg" class="direct-msg-other-foto">
                    <div class="direct-msg-other-text">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut 
                        labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco...
                    </div>
                </div>
            </div>
            <form class="direct-msg-form">
                <textarea class="direct-msg-send" placeholder="Напишите сообщение..."></textarea>
                <button type="submit">Отправить</button>
            </form>
        </section>
</template>
<script>

</script>