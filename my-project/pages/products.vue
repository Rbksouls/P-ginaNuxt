<template>
  <slot />
  <div>
    <h1>Esta es la pagina de productos</h1>
  </div>
</template>
<script setup>
definePageMeta({
  layout: "menu",
});
</script>
