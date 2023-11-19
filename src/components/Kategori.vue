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
} from "@ionic/vue";
import "swiper/css";
import "@ionic/vue/css/ionic-swiper.css";

export default defineComponent({
  components: {
    Swiper,
    SwiperSlide,
    IonContent,
    IonPage,IonGrid,IonRow,IonCol,IonCard,IonCardHeader,IonCardContent
  },
});
</script>
<template>
  <IonRow class="ion-justify-content-center">
    <IonCol size-lg="6">
      <IonRow class="ion-justify-content-center">
        <IonCol size-lg="4">
          <IonCard>
            <IonCardContent>
              <h4 class="ion-text-center">Fiksi</h4>
            </IonCardContent>
          </IonCard>
        </IonCol>
        <IonCol size-lg="4">
          <IonCard>
            <IonCardContent>
              <h4 class="ion-text-center">Fiksi</h4>
            </IonCardContent>
          </IonCard>
        </IonCol>
        <IonCol size-lg="4">
          <IonCard>
            <IonCardContent>
              <h4 class="ion-text-center">Fiksi</h4>
            </IonCardContent>
          </IonCard>
        </IonCol>
      </IonRow>
    </IonCol>
  </IonRow>
</template>