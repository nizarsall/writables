<template>
  <q-layout view="lHh Lpr lFf" class="flex flex-center">
    <q-header color="primary" class="q-pa-none bg-primary"  >
      <q-toolbar >
        <q-toolbar-title>
        <q-avatar>
            <img src="../assets/images\general/mini-logo.png">
          </q-avatar>   
        </q-toolbar-title>
        <q-tabs align="left" class="agency-30">
          <q-btn flat to="/page1" label="Home" />
          <q-btn flat to="/page2" label="services" />
          <q-btn flat to="/page3" label="library" />
          <q-btn flat to="/page3" label="platforms" />
          <q-btn outline color="secondary" label="singup/login" />
          <q-btn flat to="/page3" label="en/ar" />
        </q-tabs>
       </q-toolbar>
    </q-header>
      <div style="height:calc(100vh - 50px);z-index:-2;" class="absolute-left">
      <img src="../assets/images\general/bg-lf.png" style="height:100%"/>
      </div>
      <div style="height:calc(100vh - 50px);z-index:-2;" class="absolute-right">
      <img src="../assets/images\general/bg-rt.png" style="height:100%"/>
      </div>
      <div style="height:50%;z-index:-1;top:20%;" class="absolute-left">
      <img src="../assets/images\general/writables.png" style="height:100%"/>
      </div>
    <q-page-container class="absloute-center" style="z-index:4;width:50%">
      <router-view />
    </q-page-container>
    <q-footer class="bg-grey text-white" style="width:40%; ">
    </q-footer>

  </q-layout>
</template>

<script>
export default {
  name: 'MainLayout',
  data () {
    return {
    }
  },

}
</script>
<style scoped>


</style>
