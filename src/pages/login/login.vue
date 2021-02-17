<template>
  <div class="row justify-center">
    
    <div class=" column ">
      <div
        class="agency-60 font-bold text-secondary col-3 no-wrap"
        style=" line-height: 116px;"
      >
        where creativity begins
      </div>
      <div  class="col-9">
        <div
          class="agency-48  justify-center text-primary"
          style="text-align:center; line-height: 14px;"
        >
          Log In
        </div>
        <q-form
          @submit="onSubmit"
          @reset="onReset"
          class=" q-ma-none"
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
            <q-btn
              rounded
              label="Log in"
              type="submit"
              color="primary"
              class="q-ma-sm"
            />
          </div>
          <div
            class="helvetica-24  justify-center text-primary"
            style="text-align:center;text-decoration: underline;font-size:12px"
          >
            <strong>
              <a href="">forgot your password ? </a><br />
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
          <q-btn
            rounded
            outline
            color="secondary"
            label="entity"
            class="q-ma-sm col-2"
          />
          <q-btn
            rounded
            outline
            color="secondary"
            label="writer"
            class="q-ma-sm col-2"
          />
          <q-btn
            rounded
            outline
            color="secondary"
            label="talent"
            class="q-ma-sm col-2"
          />
        </div>
      </div>
    </div>
  </div>
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
