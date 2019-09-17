<template>
  <q-page class="flex flex-center column ">
    <img alt="Quasar logo" src="~assets/quasar-logo-full.svg" class="q-pa-lg">
    <q-card dark bordered class="bg-red-9 q-pa-md shadow-24">
      <q-card-section>
        <q-spinner
          color="accent"
          size="3rem"
        />

        <q-spinner
          color="primary"
          size="3em"
          :thickness="2"
        />

        <q-spinner
          color="primary"
          size="3em"
          :thickness="10"
        />
      </q-card-section>
    </q-card>

  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex'
}
</script>
