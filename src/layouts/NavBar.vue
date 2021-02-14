<template>
    <q-header color="primary" class="q-pa-none bg-primary">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="../assets/images\general/mini-logo.png" />
          </q-avatar>
        </q-toolbar-title>
        <q-tabs align="left" class="agency-30">
          <q-btn flat to="/" label="Home" />
          <q-btn flat to="/page2" label="services" />
          <q-btn flat to="/page3" label="library" />
          <q-btn flat to="/page3" label="platforms" />
          <q-btn outline color="secondary" label="singup/login" to="/login" />
          <q-btn flat to="/page3" label="en/ar" />
        </q-tabs>
      </q-toolbar>
    </q-header>
</template>
<script>
export default {
    name:'NavBar'
}
</script>