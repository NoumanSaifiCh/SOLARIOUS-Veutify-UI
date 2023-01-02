<template>
  <div>
    <v-row justify="space-around" class="pa-5">
      <v-avatar>
        <img src="../assets/site-logo.jpg" alt="logo">
      </v-avatar>
    </v-row>
    <div class="text-center">
      <h3>SOLARIOUS</h3>
    </div>
    <v-card class="mx-auto grey lighten-5" width="300" height="580" elevation="0">
      <!-- List Start-->
      <v-list class=" grey lighten-5">
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-poll</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Dashboard</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon> mdi-chart-bubble</v-icon>
          </v-list-item-icon>

          <v-list-item-title>Education</v-list-item-title>
        </v-list-item>
        <v-list-group sub-group class="mr-2" :value="true" prepend-icon=" mdi-book-multiple">
          <template v-slot:activator>
            <v-list-item-title>Resource</v-list-item-title>
          </template>
          <v-list-item>
            <v-list-item-icon>
              <v-icon size="14px" color="light-red"> mdi-square-rounded</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Genetics 101</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-icon>
              <v-icon size="14px" color="light-blue"> mdi-square-rounded</v-icon>
            </v-list-item-icon>
            <v-list-item-title>DNA synthesis</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-icon>
              <v-icon size="14px" color="red"> mdi-square-rounded</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Events</v-list-item-title>
          </v-list-item>
        </v-list-group>
        <v-list-item>
          <v-list-item-icon>
            <v-icon> mdi-cog-outline</v-icon>
          </v-list-item-icon>

          <v-list-item-title>Setting</v-list-item-title>
        </v-list-item>

      </v-list>
    </v-card>
    <v-spacer></v-spacer>
    <v-container class="d-flex pt-16 mt-8">
      <v-row>
        <v-btn class="mx-2" fab dark color="black">
          <v-icon dark>
            mdi-logout-variant
          </v-icon>
        </v-btn>
        <h4 class="pt-5">Log out</h4>

      </v-row>
    </v-container>
  </div>

</template>
    
<script>

export default {
  name: 'SideBar',

  data() {
    return {

    };
  }
}
</script>
    
<style scoped>

</style>