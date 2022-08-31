<template>
  <q-layout view="lHh Lpr lFf">
<!--    <q-header elevated>-->
<!--    </q-header>-->

<!--    <q-drawer>-->
<!--    </q-drawer>-->

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainLayout',
})
</script>
