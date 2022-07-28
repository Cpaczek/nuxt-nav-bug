<template>
  <div>
    <h1>Foobar</h1>
  </div>
</template>
<script setup lang="ts">

  definePageMeta({
    layout: "foolayout",
  })
  await navigateTo({ path: '/page2' })
</script>
