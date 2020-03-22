<template>
  <article class="news-card">
    <div class="news-card__header">
      <div class="news-card__profile">
        <a href="#">
          <img class="news-card__profile-foto" :src="post.userFoto" />
        </a>
        <div class="news-card__profile-info">
          <a href="#" class="news-card__profile-name">{{post.name}}</a>
          <p class="news-card__place">{{post.place}}</p>
        </div>
      </div>
      <a href="#" class="news-card__extra">
        <svg fill="#262626" height="16" viewBox="0 0 48 48" width="16">
          <circle clip-rule="evenodd" cx="8" cy="24" fill-rule="evenodd" r="4.5" />
          <circle clip-rule="evenodd" cx="24" cy="24" fill-rule="evenodd" r="4.5" />
          <circle clip-rule="evenodd" cx="40" cy="24" fill-rule="evenodd" r="4.5" />
        </svg>
      </a>
    </div>
    <div class="news-card__body">
      <img class="news-card__foto" :src="post.post" alt="Это я" srcset />
    </div>
    <div class="news-card__footer">
      <div class="news-card__icons">
        <div class="news-card__icons-left">
          <a href="#">
            <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
              <use xlink:href="@/assets/img/sprite.svg#heart" />
            </svg>
          </a>
          <a href="#">
            <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
              <use xlink:href="@/assets/img/sprite.svg#comment" />
            </svg>
          </a>
          <a href="#">
            <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
              <use xlink:href="@/assets/img/sprite.svg#msg" />
            </svg>
          </a>
        </div>
        <div class="news-card__icons-right">
          <a href="#">
            <svg xmlns="http://www.w3.org/2000/svg" width="25px" height="25px">
              <use xlink:href="@/assets/img/sprite.svg#bookmark" />
            </svg>
          </a>
        </div>
      </div>
      <div class="news-card__views">{{post.like}} отметок "Нравится"</div>
      <div class="news-card__caption">
        <span>{{post.name}}</span>
        {{post.caption}}
      </div>
      <div class="news-card__comments">
        <p v-for="comment in post.comments" :key="comment.id">
          <span>{{comment.name}}</span>
          {{comment.msg}}
        </p>
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
  props: ['post']
};
</script>