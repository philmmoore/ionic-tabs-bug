<template>
  <ion-router-outlet></ion-router-outlet>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import {IonRouterOutlet, useIonRouter} from '@ionic/vue';
export default defineComponent({
  name: 'BaseTab',
  components: { IonRouterOutlet },
  setup() {
    const router = useIonRouter()
    return {router}
  }
});
</script>
