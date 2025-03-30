<template>
<h1>Vista</h1>
<h2>{{ textoAvisualizar }}</h2>

</template>

<script>
export default {
    props: {
        textoAvisualizar: {
            type: String,
        },
    },
}
</script>