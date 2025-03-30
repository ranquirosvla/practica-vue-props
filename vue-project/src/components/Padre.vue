<script>
import Editor from './Editor.vue';
import Vista from './Vista.vue';

export default{
    data() {
        return{
            titulo:''
        }
    
    },
    components: {
        'componente-editor' : Editor,
        'componente-vista' : Vista,
    },

    props: {
        titulo: {
            type: String,
        },
    }    
  

}

   

</script>


<template>

    <div class="container">
        <h1>Texto</h1>
        <componente-editor v-bind:textoAEditar="titulo"> </componente-editor>

    </div>
    
</template>

<style>

</style>