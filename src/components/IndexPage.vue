<template>
  <v-container fluid>
    <v-row no-gutters>
      <!-- side bar -->
      <v-col md="2">
        <v-card class="pa-1 grey lighten-5" outlined tile>
          <SideBar />
        </v-card>
      </v-col>

      <!-- Today Plans -->
      <v-col md="4">
        <v-card class="pa-1 white" outlined tile>
          <TodayPlans />
        </v-card>
      </v-col>



      <v-col md="5">
        <v-card class="pa-1 grey lighten-5" outlined tile>
          <MonthlyPinned />
        </v-card>
      </v-col>

      <v-col md="1">
        <v-card class="pa-1 grey lighten-5" outlined tile>
          <ProfileDoctor />
        </v-card>
      </v-col>

    </v-row>
  </v-container>
</template>
    
<script>
import SideBar from './SideBar.vue';
import TodayPlans from './TodayPlans.vue';
import MonthlyPinned from './MonthlyPinned.vue';
import ProfileDoctor from './ProfileDoctor.vue'
export default {
  name: 'IndexPage',

  components: {
    SideBar,
    TodayPlans,
    MonthlyPinned,
    ProfileDoctor
  },


  data() {
    return {

    };
  }
}
</script>
    
<style scoped>

</style>