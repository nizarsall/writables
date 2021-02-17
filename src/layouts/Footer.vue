<template>
<div class="bg-transparent text-white">
      <div class="center column justify-center">
        <div
          class="agency-30 text-secondary absloute"
          style="text-align:center;"
        >
          GET THE APP
        </div>
        <div class="row  justify-center q-mb-md">
           <img src="../assets/images\general/google-play.png" class="justify-center q-ma-sm" style="height:7%;width:14%;left:30%"/>
           <img src="../assets/images\general/app-store.png" class="justify-center q-ma-sm" style="height:7%;width:14%;left:30%"/>
        </div>
      </div>
      <q-separator color="secondary" inset />
      <q-toolbar class="absloute-center"> 
        <q-toolbar-title>
          <q-avatar size="100px" class="q-ma-md">
            <img src="../assets/images\general/writables.png" />
          </q-avatar>
        </q-toolbar-title>
        <q-tabs class="agency-30 text-primary">
          <div class="row">
            <div class="column q-mr-md">
              <q-btn flat to="/page1" label="Home" align="left"/>
              <q-btn flat to="/page1" label="servicies" />
              <q-btn flat to="/page1" label="contact" />
            </div>
              <div class="column q-mr-md">
              <q-btn flat to="/page1" label="terms&condetions" align="left" />
              <q-btn flat to="/page1" label="privacy policy" align="left" />
              <q-btn flat to="/page1" label="writables protocol" align="left"/>
            </div>
              <div class="column q-mr-md text-secondary">
                <q-btn flat to="/page1" icon="facebook" label="facebook" align="left" />
                <q-btn flat to="/page1" icon="instagram" label="instagram" align="left" />
                <q-btn flat to="/page1" icon="link" label="linkedin" align="left" />
              </div>
          </div>
        </q-tabs>
      </q-toolbar>
</div>
    </template>