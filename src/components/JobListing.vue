<script setup>
    import jobData from '@/jobs.json';
    import { ref } from 'vue';

    const jobs = ref(jobData);
</script>

<template>
    <div v-for="job in jobs" :key="job.id">
        <h2>{{ job.title }}</h2>
    </div>
</template>
