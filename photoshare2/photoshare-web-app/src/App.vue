<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="font-weight-medium display-3">Photoshare 2</div>
      <v-spacer></v-spacer>
   
      <v-text-field light="true" height="30" placeholder="search" class="mt-5" background-color="grey lighten-1" rounded ></v-text-field>
     
      <v-btn color="light-blue" class="ml-3">Home</v-btn>
      
      <v-btn color="light-blue" class="ml-3">Search</v-btn>
      <v-btn color="light-blue" class="ml-3">Sign In/Out</v-btn>
      <v-btn color="light-blue" class="ml-3">Post</v-btn>
    </v-app-bar>

    <v-main>
   
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  
  },

  data: () => ({
    //
  }),
};
</script>
