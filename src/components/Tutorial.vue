<template>
  <div class="container">
    Tutorial{{name}}
  </div>
</template>

<script >

export default
{
  props:[name],
  name:"Tutorial"
}
</script>


<style scoped>
.container {
  margin: 2px;
  background-color:aquamarine;
  padding: 6px;
  font-size:xxx-large;
}
</style>