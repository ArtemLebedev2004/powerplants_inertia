<template>
    <div>
        <Head title="Dashboard" />
        <h1 class="mb-8 text-3xl font-bold">Dashboard</h1>
        <p class="mb-8 leading-normal">Hey there! Welcome to Ping CRM, a demo app designed to help illustrate how <a class="text-indigo-500 hover:text-orange-600 underline" href="https://inertiajs.com">Inertia.js</a> works.</p>
    </div>
</template>

<script setup>
import Layout from '../../Components/Layout.vue';
import { Head } from '@inertiajs/vue3';

defineOptions({ layout: Layout })
</script>
