<template>
  <v-container >
      <v-row >
          <v-col cols="12">
               <Avatar/>
          </v-col>
      </v-row>
  </v-container>
</template>

<script>
import Avatar from './Avatar';

export default {
    components: {
    Avatar,
  },
  data: () => ({})
};
</script>

<style scoped>
.cenas{
    color:lightcoral;
}
.cont1{
    background-color: black
    }
.row1{
    background-color: white
}
</style>