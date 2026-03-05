<template>
<h1>Jobs</h1>
<h2 v-for="job in jobs" :key="job.id"> {{ job.title }}</h2>


</template>

<script>
export default {
    data() {
        return {
            jobs: [
                { title: 'ux designer', id: 1, details: "lorem"},
                { title: 'web developer', id: 2, details: "lorem"},
                { title: 'vue developer', id: 3, details: "lorem"}
            ]
        }
    }
}
</script>

<style>

</style>