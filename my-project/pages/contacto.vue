<template>
    <div>
      <slot />
      <h1>Hola a todos!!</h1>
      <p>Soy la página de contacto...</p>
    </div>
    <NuxtLink to="/">Ir al inicio</NuxtLink>
</template>
<script setup>
  definePageMeta({
    layout: "menu"
  })
</script>