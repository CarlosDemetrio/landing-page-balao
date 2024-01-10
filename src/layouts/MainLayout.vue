<template>
  <q-layout>
    <q-header>
 <HeaderComponent/>
    </q-header>
    <q-page-container>
      <q-page>
        <router-view />
      </q-page>
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from 'vue'
import HeaderComponent from "components/headerComponent.vue";


export default defineComponent({
  name: 'MainLayout',

  components: {
    HeaderComponent
  },

  setup () {

    return {
    }
  }
})
</script>
