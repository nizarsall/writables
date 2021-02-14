<template>
  <q-layout view="lHh Lpr lFf" class="flex flex-center">
    <nav-bar></nav-bar>
    <div style="height:calc(100vh - 50px);z-index:-2;" class="absolute-left">
      <img src="../assets/images\general/bg-lf.png" style="height:100%" />
    </div>
    <div style="height:calc(100vh - 50px);z-index:-2;" class="absolute-right">
      <img src="../assets/images\general/bg-rt.png" style="height:100%" />
    </div>
    <div style="height:60%;z-index:-1;top:12%;" class="absolute-left">
      <img src="../assets/images\general/writables.png" style="height:100%" />
    </div>
    <q-page-container  style="z-index:4;width:50%;">
      <router-view />
    </q-page-container>
    <Footer> </Footer>
  </q-layout>
</template>

<script>
import Footer from './Footer.vue';
import NavBar from './NavBar.vue';
export default {
  components: { Footer, NavBar },
  name: "MainLayout",
  data() {
    return {};
  }
};
</script>
<style scoped></style>
