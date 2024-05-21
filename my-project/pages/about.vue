<template>
    <NuxtLink to="/">Ir al Inicio</NuxtLink>
    <div class="grid grid-cols-4 gap-5 mx-10">
        <div v-for=" p in products">
            <NuxtLink :to="`/products/${p.id}`">{{ p.title }}</NuxtLink>
        </div>
    </div>
    <slot />
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'products'
})
const {data: products} = await useFetch('https://fakestoreapi.com/products');
</script>