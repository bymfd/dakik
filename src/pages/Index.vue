<template>
  <q-page class="row items-center justify-evenly">
  
    <q-btn
      @click="showNotification"
      color="primary"
      label="QR kodu Okutarak Başla"
    />
  
  </q-page>
</template>

<script lang="ts">

import ExampleComponent from 'components/CompositionComponent.vue';
import { defineComponent, ref } from '@vue/composition-api';
  
export default defineComponent({
  name: 'PageIndex',
  components: { ExampleComponent },
  methods: {
    showNotification () {
    var sss="QR KOD GÖSTERİLİYOR";
      this.$q.notify(sss)
    }
  },	

});
</script>
