<template>
  <section class="timeline">
    <NewsCard v-for="post in posts" :key="post.id" v-bind:post="post" />
  </section>
</template>
<script>
import NewsCard from "@/components/NewsCard";
export default {
  data() {
    return {
      posts: [
        {
          id: 1,
          name: "UserName ",
          userFoto: require("@/assets/img/users/UserName/foto.jpg"),
          place: "Togliatti, Lenina str.",
          post: require("@/assets/img/users/UserName/news/1.jpg"),
          like: 16,
          caption: " Это я!!!",
          comments: [
            {
              id: 1,
              name: "NoName_163 ",
              msg: " Отлично выглядишь"
            },
            {
              id: 2,
              name: "UserName ",
              msg: " Спасибо"
            }
          ],
          date: "30 февраля"
        },
        {
          id: 2,
          name: "User_Name ",
          userFoto: require("@/assets/img/users/User_Name/foto.jpg"),
          place: "Togliatti, Yubileynaya str.",
          post: require("@/assets/img/users/User_Name/news/1.jpg"),
          like: 12,
          caption: " Курю трубку с ...",
          comments: [
            {
              id: 1,
              name: "UserName ",
              msg: " Отлично выглядишь ;)"
            },
            {
              id: 2,
              name: "User_Name ",
              msg: "Спасибо"
            }
          ],
          date: "31 февраля"
        }
      ]
    };
  },
  components: {
    NewsCard
  }
};
</script>