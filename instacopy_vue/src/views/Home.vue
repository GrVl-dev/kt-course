<template>
  <div class="homepage">
    <Header/>
  </div>
</template>

<script>
import Header from "@/components/Header"
export default {
  name: 'Home',
  metaInfo: {
    title: 'Instacopy'
  },
  components: {
    Header
  }
};
</script>
