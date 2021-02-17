<template>
  <q-layout view="lHh Lpr lFf">
    <nav-bar></nav-bar>

    <div style="height:calc(100vh - 50px);z-index:-2;" class="absolute-left">
      <img src="../assets/images\general/bg-lf.png" style="height:100%" />
    </div>
    <div style="height:calc(100vh - 50px);z-index:-2;" class="absolute-right">
      <img src="../assets/images\general/bg-rt.png" style="height:100%" />
    </div>
    <div class="row q-mr-none q-mt-xl q-mb-none" style="height:100%" >
      <div class="col-3  q-ma-none " >
        <img src="../assets/images\general/writables.png" style="width:100%" />
      </div>
      <div class="col-lg-6 col-md-9 column" >
        <div class="col-8  wrap">
          <router-view style="height:90%;" class=""/>
        </div>
        <div class="col-4 justify-end">
        <Footer > </Footer>
        </div>
      </div>
    </div>
  </q-layout>
</template>

<script>
import Footer from "./Footer.vue";
import NavBar from "./NavBar.vue";
export default {
  components: { Footer, NavBar },
  name: "MainLayout",
  data() {
    return {};
  }
};
</script>
<style scoped></style>
