<template>
  <v-app>
    <!-- <IndexPage/> -->
    <IndexPage/>
    
  </v-app>
</template>

<script>
//import SideBar from './components/SideBar.vue';
import IndexPage from './components/IndexPage.vue'

export default {
  name: 'App',

  components: {
    IndexPage
    
  },

  data: () => ({
    //
  }),
};
</script>
