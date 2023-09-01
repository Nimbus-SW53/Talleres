<template>



  <div class="container-category">

    <Tutorial name="math" />

    <Tutorial name="Literature" />

    <Tutorial name="Music" />

  </div>





</template>



<script>

import Tutorial from "@/components/tutorial.vue";



export default {

  name: "category",

  components: {Tutorial}

}

</script>



<style scoped>

.container-category{

  display: flex;

  flex-direction: column;

  padding: 6px;

  background-color: bisque;

  margin: 6px;

}



</style>

Naldo Reupo-Musayon Gastulo
01:53:18
<template>

  <div class="container">

    Tutorial {{name}}

  </div>



</template>



<script>

export default {

  props:['name'],

  name: "tutorial"

}

</script>



<style scoped>

.container{

  margin: 2px;

  background-color: aquamarine;

  padding: 6px;

  font-size: xxx-large;

}



</style>