<script setup>
    import jobData from '@/jobs.json';
    import { ref } from 'vue';

    const jobs = ref(jobData);
</script>

<template>
    <h1>Job Listing</h1>
    <div v-for="job in jobs" :key="job.id">
        <h2>{{abc }}</h2>
    </div>
</template>
