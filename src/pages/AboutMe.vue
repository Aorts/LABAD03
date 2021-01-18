<template>
  <div class="q-pa-md row items-start q-gutter-md">

    <q-card
      class="my-card text-white"
      style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"
    >
      <q-card-section>
        <div class="text-h6">LAB FRAMEWORK 6110110200</div>
        <div class="text-subtitle2">by STROA</div>
      </q-card-section>
<q-card-section>
  <div class="text-h6">THANYAWAT SAPPALUNN</div>
</q-card-section>
    </q-card>

    <q-card class="my-card">
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://multiplayer.net-cdn.it/thumbs/images/2017/07/04/princess-03_jpg_1024x768_crop_upscale_q85.jpg">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label>PHOTO</q-item-label>
          <q-item-label caption>by STROA</q-item-label>
        </q-item-section>
      </q-item>

      <img src="https://www.playulti.com/static/thumb/2018/9/11/attach-1539235273957.jpg">
    </q-card>
    <q-page class=" flex flex-center">
    <q-btn  color="primary" icon="home" label="Home" @click="$router.replace('/')" />
  </q-page>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 250px
</style>
