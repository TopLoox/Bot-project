<template>
  <q-page class="flex flex-center">
    <q-intersection transition="scale">
      <q-card class="flex flex-center column shadow-0 q-pa-sm">
        <img
          class="q-mt-md q-mb-sm"
          style="width: 7.5em; height: 7.5em;"
          src="~assets/logo.png"
        >

        <span class="q-mx-md">Bot project</span>
      </q-card>
    </q-intersection>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainApp'
})
</script>
