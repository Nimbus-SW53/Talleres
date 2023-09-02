<template>
  <div id="app">
    <div class="barra-superior">
      <input type="text" v-model="texto" placeholder="Ingrese su texto aquí" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      texto: ''
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.barra-superior {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 14px 0;
}

input[type="text"] {
  width: 80%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
}
</style>
