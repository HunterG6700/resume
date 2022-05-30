<template>

  <title>Home</title>
     <div  class="home" >

    <h1><big>Home</big></h1>
    <v-avatar
      size="200"
      >
   <v-img
  lazy-src="https://cdn.discordapp.com/attachments/395623156561215489/977555636428632104/Hunter.png"
  max-height="150"
  max-width="250"
  src="https://cdn.discordapp.com/attachments/395623156561215489/977555636428632104/Hunter.png"
></v-img>
      

    </v-avatar>Hunter Goller

  </div>

 

</template>

<script>
import { defineComponent } from 'vue';
import Vue from 'vue'

import colors from 'vuetify/lib/util/colors'

// Components



export default defineComponent({
  name: 'HomeView',
   theme: { dark: true },

  setup() {
    return {
      myStyle:{
            backgroundColor:"#16a085" 
            }
    };
  }
});
</script>



<style scoped>
.home {
  text-align: center;

}


</style>