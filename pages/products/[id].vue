<template>
  <div>
    <p>products details for {{ id }}</p>
  </div>
</template>

<script setup>
 const { id } = useRoute ().params
 definePageMeta({
    layout: 'products'
  })
</script>

<style>

</style>