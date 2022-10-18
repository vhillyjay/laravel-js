<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';

defineProps([
    'chirp',
])

</script>

<template>
    <Head title="Home" />
    <div>
        homehomean
        <p v-for="chirpData in chirp">{{ chirpData.message }} - {{ chirpData.id }}</p>
    </div>
</template>

