<template>
  <div class="homepage">
    <Header v-bind:navMenu="navMenu"/>
    <Timeline/>
    <Aside/>
  </div>
</template>

<script>
  import Header from "@/components/Header";
  import Timeline from "@/components/Timeline";
  import Aside from "@/components/Aside";

  export default {
    name: 'Home',
    data() {
      return {

        navMenu: {
          home: true,
          homeActive: false,
          direct: false,
          directActive: true
        }
      };
    },
    metaInfo: {
      title: 'Instacopy'
    },
    components: {
      Header,
      Timeline,
      Aside
    }
  };

</script>
