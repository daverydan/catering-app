<script setup>
import { Head } from '@inertiajs/vue3'

function alertMe() {
    alert('Alert!!!');
}
</script>

<template>
    <Head title="Home" />

    <h1>Home Page</h1>

    <button type="button" @click="alertMe">Alert Me</button>
</template>
