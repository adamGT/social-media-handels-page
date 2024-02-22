<template>
  <div id="app">
    <v-app >
      <v-main>
        <HelloWorld/>
      </v-main>
        <br>
        <br>
        <br>
      <v-footer color="#1a6aa7" class=" d-flex flex-column">
        <div class=" d-flex w-100 align-center px-4">
          <strong class="white--text">Blue Health Ethiopia</strong>
        </div>

        <div class="white--text px-4 py-2 bg-black text-center w-100">
          <strong>Copyright © 2024</strong>
        </div>
      </v-footer>
    </v-app>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),

};
</script>
<style>

#app {
  background-color: #013A65; 
}
.foot{
  background-color: #FFCC00; 
}
</style>