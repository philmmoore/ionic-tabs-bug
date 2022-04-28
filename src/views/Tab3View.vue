<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-back-button></ion-back-button>
        </ion-buttons>
        <ion-title>Tab 3 View</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 3 View</ion-title>
        </ion-toolbar>
      </ion-header>

      Hello from tab 3

    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import {IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButtons, IonBackButton} from '@ionic/vue';

export default  defineComponent({
  name: 'Tab3View',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonButtons, IonBackButton, IonPage },
});
</script>
