
/* --------------------------------- script --------------------------------- */
<script>
  import AppTitle from "./components/AppTitle.vue";
  import AppHero from "./components/AppHero.vue";


  export default {
    data(){
      return{

      };
    },

    components: {
      AppTitle,
      AppHero,
    }
  }
</script>


/* -------------------------------- template -------------------------------- */
<template>

  <div id="container">
    
    <AppTitle></AppTitle>
    <AppHero></AppHero>
    
  </div>

</template>


/* ---------------------------------- style --------------------------------- */
<style >

  #container{
    display: flex;
    flex-flow: column nowrap;
    align-items: center;

  }
  
</style>