<template>
    
    <div class="f">
        <hr>
        <h2>ComponentF</h2>
        <h2>{{ user }} -- {{ employeeId }} -- {{ company }}</h2>
    </div>
</template>

<script>
    export default {
        name:'ComponentF',
        inject: ['user','employeeId','company']
        
    }
</script>

<style scoped>
.f{color: aliceblue;}
</style>