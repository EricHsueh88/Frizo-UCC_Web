<template>
  <div class="HomePage">
    <Navbar></Navbar>
    <menubar></menubar>
    <Banner></Banner>
    <ContentList></ContentList>
    <!-- <router-link to="/store">到 Store 測試頁</router-link> -->
  </div>
</template>

<script>
import ContentList from "@/components/ContentList";
import Navbar from "@/components/base/Navbar";
import Menubar from "@/components/base/Menubar";
import Banner from "@/components/Banner";

export default {
  name: "HomePage",
  components: {
    ContentList,
    Navbar,
    Menubar,
    Banner
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
