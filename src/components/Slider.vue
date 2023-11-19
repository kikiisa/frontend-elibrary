<template>
 <IonRow class="ion-justify-content-center">
    <IonCol size-lg="6">
      <IonCard>
        <IonCardContent>
            <swiper>
                <swiper-slide>Slide 1</swiper-slide>
                <swiper-slide>Slide 2</swiper-slide>
                <swiper-slide>Slide 3</swiper-slide>
            </swiper>
        </IonCardContent>
      </IonCard>   
    </IonCol>
 </IonRow>

</template>
  
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