<template>
  <v-app>
    <v-app-bar app color="#ffffff" flat>
      <Header/>
    </v-app-bar>
    <v-main>
    <router-view/>
    </v-main>
  </v-app>
</template>
<script>
import Header from './components/Header.vue'
export default {
  name: 'App',
  components: {
    Header,
  },
  
}
</script>