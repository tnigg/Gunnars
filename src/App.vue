<script setup>
import TheHeader from "./components/TheHeader.vue";
import ContactBar from "./components/ContactBar.vue";
import Services from "./components/Services.vue";
import HeroPage from "./components/HeroPage.vue";
import TheFooter from "./components/TheFooter.vue";
</script>

<template>  
<div>  
    <TheHeader class="fixed hidden md:flex min-w-fit" />  

     <!-- <div id="bg_img" class="relative block min-h-screen bg-blue-100 -z-20">     -->
     <div class="md:pt-28">  <!-- DECRESE PADDING TOP IF NAVIHIGHT CHANGES -->     
      <ContactBar />      
     </div>    

     <!-- HERO CONTENT  -->
     <div class="md:pt-40"> <!-- INCREASE / DECRESE PADDING TOP IF HEADERHIGHT CHANGES -->
     <HeroPage /> 
     </div>  
     <!-- </div>  END TRANSPARENT ???????? BACKGROUND -->

   <div class="pt-36">
     <Services class="pt-10 " />
   </div>

   <div>
     <TheFooter class="mt-16"/>
   </div>
</div>    
</template>


