<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { IonHeader,IonToolbar,IonTitle,IonIcon } from '@ionic/vue';
</script>
<template>
  <IonHeader>
    <IonToolbar color="primary">
      <IonTitle class="ion-text-center"><strong>E-LIBRARY</strong></IonTitle>
    </IonToolbar>
  </IonHeader>
  <RouterView />
</template>
