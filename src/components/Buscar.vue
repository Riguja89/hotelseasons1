<template>
  <div id="buscar">
    <h1 class="tittle">Buscar Festividades</h1>
    <hr> 
    <div class="search-wrapper">
      <label for="ciudad">Ciudad:</label>
      <input type="text" style="border: solid 2px" placeholder="Buscar ciudades.."/>
      <label for="fecha">Fecha:</label>
      <input type="date" style="border: solid 2px">
      <br>
      <br>
      <button v-on:click="fetch">CONSULTAR</button>
      <div v-for="nombre of nombres" v-bind:key="nombre.id">
        <h2>{{ nombre }}</h2>
      </div>
    </div>
  </div>
</template>


<script>

</script>