<template>
<h1>Job Details Page</h1>
job id is {{ id }}
</template>

<script>
export default {
    data() {
        return {
            id: this.$route.params.id
        }
    }
}
</script>

<style>

</style>