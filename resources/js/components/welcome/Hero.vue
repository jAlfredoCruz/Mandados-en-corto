<script setup lang="ts">
    import Whatsapp from '../svgs/Whatsapp.vue';
    import Location from '../svgs/Location.vue';
    import IconField from 'primevue/iconfield';
    import InputIcon from 'primevue/inputicon';

</script>

<template>
   <div class="relative bg-gradient-to-r from-purple-600 to-blue-600 h-screen text-white overflow-hidden">
  <div class="absolute inset-0">
    <img src="images/corto-hero.jpg" alt="Background Image" class="object-cover object-center w-full h-full" />
    <div class="absolute inset-0 bg-black opacity-50"></div>
  </div>

  <div class="relative z-10 flex flex-col justify-center items-center h-full text-center">
    <h1 class="text-5xl font-bold leading-tight mb-4">¿Donde quieres recibir tu compra?</h1>
    <IconField class="bg-white ">
        <InputIcon class="">
            <Location />
        </InputIcon>
        <InputText  placeholder="Search" />
    </IconField>
    <p class="text-4xl font-bold text-white mb-8 flex items-center justify-between"><span class="m-3">O haz el pedido por Whatsapp</span> <Whatsapp /> <span>4871450515</span> </p>
  </div>
</div>

</template>


