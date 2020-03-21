<template>
  <div class="homepage">
    <Header/>
    <section class="timeline">
      <NewsCard/>
    </section>
    <Aside/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import NewsCard from "@/components/NewsCard";
import Aside from "@/components/Aside";

export default {
  name: 'Home',
  metaInfo: {
    title: 'Instacopy'
  },
  components: {
    Header,
    NewsCard,
    Aside
  }
};
</script>
