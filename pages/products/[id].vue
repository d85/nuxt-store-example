<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid quas incidunt odio ipsa explicabo, repellat porro numquam hic fugit eligendi.</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params

  definePageMeta({
    layout: 'products'
  })
</script>

<style scoped>

</style>