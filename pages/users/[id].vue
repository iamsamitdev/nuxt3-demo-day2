<script setup lang="ts">

    // อ่านค่าจาก params ที่ส่งมาจาก NuxtLink
    const route = useRoute()
    console.log(route.params.id)
    console.log(route.query.type)
    console.log(route.query.page)
    
</script>

<template>
    <div>
        <h1>User Page</h1>
        <p>User: {{ $route.params.id }}</p>
        <p>Type: {{ $route.query.type }}</p>
        <p>Page: {{ $route.query.page }}</p>
    </div>
</template>

<style scoped>

</style>