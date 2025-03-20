<script>
import Editor from './Editor.vue';

export default{
    data() {
        return{
            titulo:''
        }
    
    },
    components: {
        'componente-editor' : Editor,
    },

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