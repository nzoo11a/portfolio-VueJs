<template>
    <v-app-bar app color="black" dark flat class="px-12" >
      <v-btn >
      </v-btn>
      
  
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')" class="text-blue">Home</v-btn>
      <v-btn text @click="scroll('about')"  >A propos</v-btn>
      <v-btn text @click="scroll('services')" >Réalisations</v-btn>
      <v-btn text @click="scroll('contact')"  > Contact</v-btn>
    </v-app-bar>
  </template>
  
  <script>
  export default {
    methods: {
      scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({ behavior: "smooth" });
      },
    },
  };
  </script>
  
  <style>
  </style>