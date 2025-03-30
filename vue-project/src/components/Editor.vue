<template>
    <section>
      <h1>Editor</h1>
      <input v-bind:value="textoAEditar" />
   
  
    </section>
  </template>
  
  <script>

  
  export default {
    props: {
      textoAEditar: {
        type: String,
      },
     
    },
  }
  </script>