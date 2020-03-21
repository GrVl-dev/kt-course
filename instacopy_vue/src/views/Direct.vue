<template>
  <div class="direct">
    <Header/>
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
  }
}
</script>
