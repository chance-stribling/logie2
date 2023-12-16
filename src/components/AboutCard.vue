<template>
  <div class="main pa-10">
    <h1 class="text-white text-center">About Me</h1>
    <div class="content">

      <v-col cols="6" class="content d-flex flex-column align-center pa-5">
        <div
        class="pa-5 rounded"
        style=" min-width: 400px; text-align: justify; color: white;"
        >
        <p>Hi, I'm Logan! <br /></p>
        <p>
          At 19, I'm on a journey of self-discovery, navigating life's twists and turns with a
          heart rooted in Louisiana and aspirations reaching for the sky in Tennessee. I'm
          captivated by the melodies of life, seeking harmony between the familiarity of my roots
          and the uncharted territories of my dreams. Originally from Louisiana, the bayou's
          warmth still flows in my veins, carrying the rich tapestry of Cajun culture and the
          spirited essence of Southern hospitality. But now, I find myself in the rolling hills of
          Tennessee, drawn by its vibrant energy and the promise of new beginnings.
        </p>
        <p>
          Currently, I'm on the brink of a thrilling chapter—college. As I weave through
          applications and ponder the infinite possibilities ahead, I'm eager to immerse myself in
          knowledge, fueled by an insatiable curiosity for learning and a passion for
          understanding the world. Yet, beyond academics, I'm on a quest for spiritual alignment.
          In the quiet moments, I seek solace in nature's embrace, finding meaning in the whispers
          of the wind and the rustle of leaves. Exploring spirituality, I'm discovering the depths
          of my soul, piecing together the mosaic of beliefs that resonate with my essence. Life's
          a canvas, and I'm embracing each stroke with open arms, painting my story with
          experiences that shape my identity and fuel my aspirations.
        </p>
      </div>
    </v-col>
    <v-col cols="6" class="d-flex flex-column align-center">
      <img
      src="../assets/images/redhead.jpg"
      alt=""
      class="rounded-lg"
      style="width: 400px; height: auto"
      />
    </v-col>
  </div>
  </div>
</template>
<style scoped>
.main {
  height: fit-content;
  width: 100vw;
  background-color: black;
}
p {
  margin-bottom: 25px;
}
.content{
  display: flex;
  flex-direction: row;
}
@media only screen and (max-width: 1000px) {

.content{
  display: flex;
  flex-direction: column-reverse;
  justify-content: center;
  align-items: center;
}
.main{
  height: 180vh;
}
} 
</style>
