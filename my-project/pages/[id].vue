<template>
    <div>
        <h1>
            Catalogo
        </h1>
        <p>Detalle del articulo{{ id }}</p>
    </div>
</template>
<script setup>
    const { id } = useRoute().params
</script>