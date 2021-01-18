<template>
<div class="q-pa-md">
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="https://cdn.quasar.dev/img/mountains.jpg"
    >
  </q-page>
  <q-page class=" flex flex-center">
    <q-btn  color="primary" icon="home" label="About me" @click="$router.replace('/aboutme')" />
  </q-page>
  </div>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
