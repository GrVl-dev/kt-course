<template>
  <div class="direct">
    <Header v-bind:navMenu="navMenu"/>
    <DirectBox/>
  </div>
</template>
<script>
import Header from "@/components/Header";
import DirectBox from "@/components/DirectBox";

export default {
  name: 'Direct',
    metaInfo: {
    title: 'Direct'
  },
  components: {
    Header,
    DirectBox
  },
  data() {
    return {
      navMenu: {
        home: false,
        homeActive: true,
        direct: true,
        directActive: false
      }
    }
  }
}
</script>
