<template>
   <v-row>
     <v-col>
       <v-card
              class="ma-0 pa-0"
              height="460vh"
              color='#1F7087'
              dark
            >

              <div class="d-flex flex-no-wrap justify-space-between">
                <v-avatar
                  class="ma-3"
                  size="125"
                  tile
                >
                  <v-img src="../assets/logo.png"></v-img>
                </v-avatar>
                <div>
                  <v-card-title
                    class="headline"
                    
                  >texto</v-card-title>
  
                  <v-card-subtitle >cenas</v-card-subtitle>
                </div>
  
                
              </div>
            </v-card>
     </v-col>
   </v-row>

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
  font-weight: bold;
  color: whitesmoke;
}
</style>