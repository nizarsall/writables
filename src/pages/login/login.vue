<template>
  <q-page class="flex column flex-center">
    <div
      class="agency-60 font-bold justify-center text-secondary flex flex-center"
      style="text-align:center; line-height: 116px;"
    >
      where creativity begins
    </div>
    <div style="width:40%">
      <div
        class="agency-48  justify-center text-primary"
        style="text-align:center; line-height: 14px;"
      >
        Log In
      </div>
      <q-form
        @submit="onSubmit"
        @reset="onReset"
        class="q-gutter-md q-ma-none"
        align="center"
        style="font-size:16px;line-height: 14px;"
      >
        <q-input
          v-model="username"
           placeholder="username"
          :dense="dense"
          color="secondary"
          class="q-ma-none q-pa-none text-secondary"
          style="line-height: 14px;font-size:16px;"
        />

        <q-input
          type="password"
          v-model="password"
          placeholder="password"
          :dense="dense"
          color="secondary"
          class="q-ma-none q-pa-none text-secondary"
          style="line-height: 14px;font-size:16px;"
        />

        <div>
          <q-btn rounded label="Log in" type="submit" color="primary" class="q-mb-none"/>
        </div>
        <div
          class="helvetica-24  justify-center text-primary"
          style="text-align:center;text-decoration: underline;font-size:12px" >
         <strong>
          <a href="">forgot your password ? </a><br/>
          <a href=""> singup with facebook </a>
          </strong>
        </div>
      </q-form>
            <div
        class="agency-48  justify-center text-primary q-ma-md"
        style="text-align:center; line-height: 24px;"
      >
        sign up
      </div>
      <div class="row justify-center">
          <q-btn rounded outline color="secondary" label="entity"  class="q-ma-sm"/>
          <q-btn rounded outline color="secondary" label="writer"  class="q-ma-sm"/>
          <q-btn rounded outline color="secondary" label="talent" class="q-ma-sm"/>
      </div>
    </div>
  </q-page>
</template>
<script>
export default {
  data() {
    return {
      dense: false
    };
  }
};
</script>
