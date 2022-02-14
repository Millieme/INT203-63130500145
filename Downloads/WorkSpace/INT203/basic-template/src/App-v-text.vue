<script setup>
const msg = 'Hello'
const counter = 1
</script>
 
<template>
<h1>{{ msg.toLowerCase() }}</h1>
<p v-text="(counter += 10)"></p>
</template>
 
<style>

</style>