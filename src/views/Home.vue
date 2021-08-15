<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Hacker News</ion-title>
        <ion-buttons slot="primary">
          <ion-button href="/settings">
            <ion-icon slot="icon-only" :icon="settingsOutline"></ion-icon>
          </ion-button>
        </ion-buttons>
      </ion-toolbar>
    </ion-header>

    <ion-content>
      <ion-list>
        <ion-item>
        </ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonItem, IonList, IonIcon } from '@ionic/vue';
import { defineComponent } from 'vue';
import { settingsOutline } from 'ionicons/icons';

export default defineComponent({
  name: 'Home',
  components: {
    IonContent,
    IonHeader,
    IonIcon,
    IonPage,
    IonTitle,
    IonToolbar,
    IonItem,
    IonList,
  },
  setup() {
    return {
      settingsOutline,
    }
  },
});
</script>

<style scoped>

</style>
