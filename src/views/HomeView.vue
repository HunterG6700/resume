<template>

  <title>Home</title>
     <div  class="home" >


    <v-avatar
      size="200"
      >
   <v-img
  lazy-src="https://cdn.discordapp.com/attachments/395623156561215489/977555636428632104/Hunter.png"
  max-height="150"
  max-width="250"
  src="https://cdn.discordapp.com/attachments/395623156561215489/977555636428632104/Hunter.png"
></v-img>
      

    </v-avatar> <font size="+10"><big>Hunter Goller </big> </font>
          <!--phoine number-->
    <p>
      <big>Phone Number:</big>
    </p>
    <p>
      <a href="tel:+1-814-289-9650">(814) 289-9650</a>
    </p>
      <p>
      <big> Socials:</big>
    </p>
    <p>
      <a href="https://www.linkedin.com/in/hunter-goller/">LinkedIn</a>
    </p>
    <p>
      <a href="https://github.com/HunterG6700">Github</a>
    </p>

    <p>
      <a href="mailto:hgoller6700@gmail.com">Email</a>
    </p>


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
          "HEllo": "World",
    }
  }
            
});
</script>



<style scoped>
.home {
  text-align: center;

}


</style>