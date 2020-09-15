<template>
  <v-container
  fluid
  fill-height
  class="containers">
    <v-row align="start">
      
      <v-col cols="12" class="cenas1">
        <v-card height="400px" shaped="true">
          <v-card-title class="justify-center"> Hire Me! </v-card-title>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'Avatar',

    data: () => ({
    }),
  }
</script>

<style scoped>
.cenas {
  background: red
}
.cenas1 {
  background: green
}
.cenas2 {
  background: lightblue
}
.rounded-card{
    border-radius:50px;
}
.containers {
  background: lightgrey
}
.justify-center{
  font-family: "Lucida Console", Courier, monospace;
  font-size: 58px;
}
</style>