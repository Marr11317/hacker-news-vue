<template>
    <ion-page>
      <ion-header>
        <ion-toolbar>
          <ion-buttons slot="start">
            <ion-back-button default-href="/home"></ion-back-button>
          </ion-buttons>
          <ion-title>Settings</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content>
        <ion-list>
          <ion-item>
            <ion-label>Username</ion-label>
            <!-- <ion-input type="text" v-model="username"></ion-input> -->
            <ion-input type="text"></ion-input>
          </ion-item>
        </ion-list>
      </ion-content>
    </ion-page>
  </template>

<script lang="ts">
    import {
      IonBackButton,
      IonButtons,
      IonContent,
      IonHeader,
      IonPage,
      IonTitle,
      IonToolbar,
      IonInput,
      IonLabel,
      IonList,
    } from '@ionic/vue';
    import { defineComponent } from 'vue';

    export default defineComponent({
      name: 'Settings',
      components: {
        IonBackButton,
        IonButtons,
        IonContent,
        IonHeader,
        IonPage,
        IonTitle,
        IonToolbar,
        IonInput,
        IonLabel,
        IonList,
      }
    });
  </script>
