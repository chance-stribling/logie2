<script>
import TypeIt from 'typeit'
export default {
  methods: {
    type: function () {
      new TypeIt('#element', {
        speed: 60
      })
        .type("Opportunities don't happen.")
        .pause(500)
        .break()
        .type('You create them.')
        .go()
    }
  },
  mounted() {
    this.type()
  }
}
</script>
<template>
  <v-toolbar class="toolbar">
    <v-toolbar-title>Logan J. Gibson</v-toolbar-title>

    <v-spacer></v-spacer>

    <v-app-bar-nav-icon></v-app-bar-nav-icon>
  </v-toolbar>
  <div class="titleCard">
    <h1 id="element"></h1>
  </div>
</template>
<style scoped>
.toolbar {
  position: absolute;
  color: white;
  background-color: transparent;
}
.titleCard {
  height: 100vh;
  width: 100vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  background: url('../assets/images/black.png');
}
#element{
  font-size: 56px;
}
@media only screen and (max-width: 1000px) {

  #element{
    font-size: 30px;
  }
} 

</style>
