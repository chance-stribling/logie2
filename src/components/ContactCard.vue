<template>
    <div style="width: 100vw; background-color: white" class="pa-10">
      <h1 class="text-black text-center mb-10">Contact Me</h1>
      <v-row>
  
        <v-col class="d-flex flex-column justify-center align-center">
          <v-card style="height: 500px; width: 600px" class="pa-5" color="black">
            <v-text-field class="mb-5" label="Name" hide-details="auto"></v-text-field>
            <v-text-field  class="mb-5" label="Email" hide-details="auto"></v-text-field>
            <v-textarea clearable  class="mb-5" label="Message (Please be nice)"></v-textarea>
            <v-btn color="white">Send</v-btn>
            <p class="mt-10">Shoot me a message and I'll respond as soon as I can! Thanks for stopping by!</p>
          </v-card>
        </v-col>
        <v-col class="d-flex flex-column align-center justify-center text-black">
          <h1 class="">Check out my socials!</h1> 
          <div class="d-flex flex-row">
            <h3 class="mr-5"><v-icon icon="mdi-twitter"></v-icon></h3> 
            <h3 class="mr-5"><v-icon icon="mdi-linkedin"></v-icon></h3> 
            <h3><v-icon icon="mdi-instagram"></v-icon></h3> 
          </div>
        </v-col>
      </v-row>
    </div>
  </template>
  
  <style></style>