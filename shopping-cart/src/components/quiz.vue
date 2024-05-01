<template>
    <ion-list>
      <ion-item>
        <ion-input label="Id"  label-placement="stacked" placeholder="Ingrese el id"></ion-input>
      </ion-item>
  
      <ion-item>
        <ion-input label="Codigo dane" label-placement="stacked" placeholder="Ingrese el codigo dane"></ion-input>
      </ion-item>
  
      <ion-item>
        <ion-input label="Nombre" label-placement="stacked" placeholder="Ingrese el nombre"></ion-input>
      </ion-item>
  
    </ion-list>
  </template>
  
  <script lang="ts">
    import { IonInput, IonItem, IonList } from '@ionic/vue';
    import { defineComponent } from 'vue';
  
    export default defineComponent({
      components: { IonInput, IonItem, IonList },
    });
  </script>