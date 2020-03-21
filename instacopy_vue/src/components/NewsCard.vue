<template>
    <article class="news-card">
        <div class="news-card__header">
            <div class="news-card__profile">
                <a href="#">
                    <img class="news-card__profile-foto" src="@/assets/img/users/UserName/foto.jpg">
                </a>
                <div class="news-card__profile-info">
                    <a href="#" class="news-card__profile-name">UserName</a>
                    <p class="news-card__place">Togliatti, Lenina str.</p>
                </div>
            </div>
            <a href="#" class="news-card__extra">
                <svg fill="#262626" height="16" viewBox="0 0 48 48" width="16">
                    <circle clip-rule="evenodd" cx="8" cy="24" fill-rule="evenodd" r="4.5"></circle>
                    <circle clip-rule="evenodd" cx="24" cy="24" fill-rule="evenodd" r="4.5"></circle>
                    <circle clip-rule="evenodd" cx="40" cy="24" fill-rule="evenodd" r="4.5"></circle>
                </svg>
            </a>
        </div>
        <div class="news-card__body">
            <img class="news-card__foto" src="@/assets/img/users/UserName/news/1.jpg" alt="Это я" srcset="">
        </div>
        <div class="news-card__footer">
            <div class="news-card__icons">
                <div class="news-card__icons-left">
                    <a href="index.html">
                        <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
                            <use xlink:href="@/assets/img/sprite.svg#heart"></use>
                        </svg>
                    </a>
                    <a href="index.html">
                        <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
                            <use xlink:href="@/assets/img/sprite.svg#comment"></use>
                        </svg>
                    </a>
                    <a href="index.html">
                        <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
                            <use xlink:href="@/assets/img/sprite.svg#msg"></use>
                        </svg>
                    </a>
                </div>
                <div class="news-card__icons-right">
                    <a href="index.html">
                        <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
                            <use xlink:href="@/assets/img/sprite.svg#bookmark"></use>
                        </svg>
                    </a>
                </div>

            </div>
            <div class="news-card__views">16 отметок "Нравится"</div>
            <div class="news-card__caption"><span>UserName </span> Это Я!!!</div>
            <div class="news-card__comments">
                <p><span>NoName_163 </span> Отлично выглядишь ;)</p>
                <p><span>UserName </span> Спасибо</p>
            </div>
            <div class="news-card__date">30 февраля</div>
            <div class="news-card__add-comment">
                <form class="news-card__comment-area">
                    <textarea type="text" placeholder="Добавьте комментарий..."></textarea>
                    <button type="submit">Опубликовать</button>
                </form>
            </div>
        </div>
    </article>
</template>

<script>
export default {
    name: "NewsCard",

};

</script>