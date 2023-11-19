<script>
import { defineComponent } from "vue";
import { Swiper, SwiperSlide } from "swiper/vue";
import { IonContent, IonPage } from "@ionic/vue";
import {
  IonGrid,
  IonRow,
  IonCol,
  IonCard,
  IonCardHeader,
  IonCardContent,
  IonCardTitle,
  IonCardSubtitle,
  IonButton
} from "@ionic/vue";
import "swiper/css";
import "@ionic/vue/css/ionic-swiper.css";

export default defineComponent({
  components: {
    Swiper,
    SwiperSlide,
    IonContent,
    IonPage,
    IonGrid,
    IonCardTitle,
    IonRow,
    IonCol,
    IonCard,
    IonCardHeader,
    IonCardContent,
    IonCardSubtitle,
    IonButton
  },
});
</script>
<template>
  <IonRow class="ion-justify-content-center">
    <IonCol size-lg="6">
      <ionCard>
        <IonRow>
          <IonCol size="4">
            <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/card-media.png" />
          </IonCol>
          <IonCol size="8">
              <ionCardHeader>
                <IonCardTitle>Belajar Pemrograman Web</IonCardTitle>
                <IonCardSubtitle>Martin Powler</IonCardSubtitle>
              </ionCardHeader>
              <IonCardContent>
                Here's a small text description for the card content. Nothing more,
                nothing less.<br>
                <IonButton color="success">Pinjam Buku</IonButton>
                <IonButton color="danger">SOLD OUT</IonButton>
              </IonCardContent>
          </IonCol>
        </IonRow>
      </ionCard>
    </IonCol>
  </IonRow>
</template>
<style scoped>
    img {
  width: 100%; /* Atur lebar gambar */
  height: 100%; /* Atur tinggi gambar */
  object-fit: cover; /* Objek gambar akan menyesuaikan dan diatur untuk mengisi sepenuhnya div tanpa merubah proporsi */
    }
</style>