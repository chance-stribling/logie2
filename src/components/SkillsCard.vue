<template>
  <div class="cover d-flex justify-center align-center">


          <h1 class="text-uppercase" id="billboard">
            SKILLS 
          </h1>

  </div>
  <div class="main3" id="skills">
    <h1 style="text-align: center; padding: 50px;"><b>SKILLS</b></h1>
      <v-row class="d-flex justify-center">
        <v-card class="prevent-select card mx-5 my-1" :id="'card'+ skill.id" v-for="skill in skills" @mouseover="backgroundChange(skill.title)">
          <v-card-title class="shrink text-uppercase text-center">{{ skill.title }}</v-card-title>

        </v-card>
      </v-row>
  </div>
</template>
<style scoped>
.cover{
    height: 15%;
  width: 100vw;
  position: absolute;
  background-color: transparent;
  font-size: 50px;
  color: white;
  text-align: center;
}
#billboard{
  transform: translateY(100%);
}
.main3 {
    min-height: 100vh;
    width: 100vw;
    background-color: black;
    color: white;
    padding-bottom: 50px;
}
.prevent-select {
    
    user-select: none; /* Standard syntax */
}
.card:hover {
    scale: 1.1;
    color: black;
    opacity: 70%;
}
.card{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px;
    width: 20%;
    opacity: 20%;
}
@media screen and (max-width: 1000px) {
  #billboard{
  display: none;
}
.card{
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 10px;
    width: 40%;
    opacity: 100%;
}
.cover{

  font-size: 20px;
}
.shrink{
    font-size: 15px;
}
}


</style>
<script>
export default {
  methods:{
    backgroundChange: function(name){
        document.getElementById('billboard').innerHTML= name;   

    }
  },
  data: () => ({
    date: null,
    skills: [
      {
        title: 'customer service',
        tag: 'language',
        id:1,
        shaped: false


      },
      {
        title: 'cash handling',
        tag: 'language',
        id:2,
        shaped: false
      },
      {
        title: 'food safety',
        tag: 'language',
        id:3,
        shaped: false
      },
      {
        title: 'critical thinking',
        tag: 'language',
        id:4,
        shaped: false
      },
      {
        title:  'creativity',
        tag: 'language',
        id:5,
        shaped: false
      },
      {
        title: 'microsoft office',
        tag: 'language',
        id:6,
        shaped: false
      },
      {
        title: 'active listening',
        tag: 'language',
        id:7,
        shaped: false
      },
      {
        title: 'patience',
        tag: 'language',
        id:8,
        shaped: false
      },
      {
        title: 'time management',
        tag: 'other',
        id:16,
        shaped: false
      },
      {
        title: 'organization',
        tag: 'other',
        id:9,
        shaped: false
      },
      {
        title: 'problem solving',
        tag: 'other',
        id:9,
        shaped: false
      },
      {
        title: 'empathy',
        tag: 'other',
        id:9,
        shaped: false
      }
    ]
  })
}
</script>