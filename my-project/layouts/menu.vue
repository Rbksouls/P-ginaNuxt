<script lang="ts" setup></script>

<template>
  <div class="menu">
    <ul class="">
      <li>
        <a href="" class=""><NuxtLink to="/contacto">Contacto</NuxtLink></a>
      </li>

      <li>
        <a href="" class=""><NuxtLink to="/about">about</NuxtLink></a>
      </li>

      <li>
        <a href="" class=""><NuxtLink to="/productos">Tienda</NuxtLink></a>
      </li>
    </ul>
  </div>
  <NuxtLink to="/">Inicio</NuxtLink>
</template>

<style scoped>
.menu{
  display: flex;
  justify-content: center;
  margin-top: 20px;
}
ul {
  display: flex;
  gap: 20px;
}
li{
  background-color: #6c8faf;
  color: white;
  list-style: none;
  padding: 20px;
  border-radius: 20px;
  transition:transform;
  transition-duration: 500ms;
  font-family: sans-serif;
  font-weight: bold;
}
li:hover{
  transform: scale(1.2)
}
/* Color Theme Swatches in Hex 
.Address-Bar-1-hex { color: #4E7DA6; }
.Address-Bar-2-hex { color: #2A4359; }
.Address-Bar-3-hex { color: #B0C6D9; }
.Address-Bar-4-hex { color: #DCE8F2; }
.Address-Bar-5-hex { color: #3F6F8C; }*/

/* Color Theme Swatches in RGBA 
.Address-Bar-1-rgba { color: rgba(77, 124, 165, 1); }
.Address-Bar-2-rgba { color: rgba(41, 67, 89, 1); }
.Address-Bar-3-rgba { color: rgba(175, 197, 216, 1); }
.Address-Bar-4-rgba { color: rgba(220, 232, 242, 1); }
.Address-Bar-5-rgba { color: rgba(63, 110, 140, 1); }

/* Color Theme Swatches in HSLA 
.Address-Bar-1-hsla { color: hsla(208, 36, 47, 1); }
.Address-Bar-2-hsla { color: hsla(208, 36, 25, 1); }
.Address-Bar-3-hsla { color: hsla(208, 34, 76, 1); }
.Address-Bar-4-hsla { color: hsla(208, 46, 90, 1); }
.Address-Bar-5-hsla { color: hsla(202, 37, 39, 1); } */
</style>
