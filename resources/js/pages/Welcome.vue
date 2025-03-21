<script setup lang="ts">
import { Head } from '@inertiajs/vue3';
import Header from '../components/welcome/Header.vue';
import Hero from '../components/welcome/Hero.vue';
</script>

<template>
    <Head title="Welcome">
        <link rel="preconnect" href="https://rsms.me/" />
        <link rel="stylesheet" href="https://rsms.me/inter/inter.css" />
    </Head>
    <div class="flex flex-col h-screen">
        <Header />
        <Hero class="flex-grow"/>
    </div>
</template>
