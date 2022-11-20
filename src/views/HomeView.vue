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
      <v-img src="https://cdn.discordapp.com/attachments/1043915887117353081/1043916158342004887/PngItem_202269.png" aspect-ratio="20" />
        <big>Phone Number:</big> 
    </p>
    <p>
      <a href="tel:+1-814-289-9650">(814) 289-9650</a>
    </p>
      <p>
      <big> Socials:</big>
    </p>
    <p>
      <v-img src="https://assets.stickpng.com/images/58e91afdeb97430e81906504.png" aspect-ratio="20" />
      <a href="https://www.linkedin.com/in/hunter-goller/">LinkedIn</a>
    </p>
    <p>
      <v-img src="https://logos-world.net/wp-content/uploads/2020/11/GitHub-Logo.png" aspect-ratio="20" />
      <a href="https://github.com/HunterG6700">Github</a>
    </p>

    <p>
      <v-img src="https://cdn.discordapp.com/attachments/1043915887117353081/1043919161866330132/baseline_email_black_24dp.png" aspect-ratio="20" />
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