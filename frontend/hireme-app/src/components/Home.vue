<template>
  <v-container fluid fill-height class="cenas pa-0" >
      <v-row class="row1 pa-0">
          <v-col class="pa-0" cols="12">
              <v-row :align="self">
               <Avatar/>
              </v-row>
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
    background-color:lightcoral;
    align-items: flex-start;
}
.cont1{
    background-color: black;
    }
.row1{
    background-color: white;

}
</style>