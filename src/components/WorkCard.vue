<template>
  <div class="main pa-10">
    <h1 class="text-center text-white mb-10">Work History</h1>
    <v-row class="justify-center mt-10">
      <v-card class="mr-10 d-flex flex-column align-center" height="500px" width="500px" style="background-color: rgba(0,0,0,0.5);">
        <v-card-title class="text-white"> Pal's Sudden Service </v-card-title>
        <div class="pals" style="width: 90%; height: 200px; "></div>
        <v-card-text class="text-justify text-white" style="font-size: 15px;">
          My role involved warmly engaging with customers, accurately handling orders, and preparing
          menu items following precise guidelines. I ensured strict adherence to food safety
          measures, managed cash transactions, and maintained a clean, organized environment.
          Collaborating seamlessly with my team members, I supported a positive and efficient
          workplace. I thrive in a fast-paced setting, showcasing excellent communication and
          multitasking skills, prioritizing customer satisfaction, and contributing to our dynamic
          team’s commitment to providing an outstanding dining experience.
        </v-card-text>
      </v-card>
      <v-card class="mr-10 d-flex flex-column align-center" height="500px" width="500px" style="background-color: rgba(0,0,0,0.5);">
        <v-card-title class="text-white"> Genuine Foods </v-card-title>
        <div class="genuine" style="width: 90%; height: 200px"></div>
        <v-card-text class="text-justify text-white" style="font-size: 15px;">
          As a Line Cook at Lee's McRae College cafeteria, I played a pivotal role in delivering
          delicious and nutritious meals to students and faculty. My responsibilities included
          proficiently preparing a variety of dishes, adhering to recipes, and ensuring food quality
          met our high standards. I worked collaboratively with the kitchen team, maintaining a
          clean and organized workspace while following strict food safety protocols. Thriving in a
          fast-paced environment, I prioritize efficiency without compromising on taste. I
          contributed to a positive dining experience by executing precise cooking techniques and
          embracing creativity in delivering flavorful meals for the college community.
        </v-card-text>
      </v-card>
    </v-row>
  </div>
</template>
<style scoped>
.main {
  width: 100vw;
  background: url('../assets/images/swirls.jpg')
}
.pals {
  background: url('../assets/images/pals.jpg');
  background-size: cover;
  background-position: top;
}
.genuine {
  background: url('../assets/images/gen.png');
  background-size: contain;
  background-position: center;
  background-color: black;
}
</style>
