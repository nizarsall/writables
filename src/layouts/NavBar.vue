<template>
    <q-toolbar >
        <q-toolbar-title slot="header">
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
</template>
<script>
export default {
    name:'NavBar'
}
</script>