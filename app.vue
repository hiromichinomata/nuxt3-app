<template>
  <div>
    <NuxtLayout :name='layout'>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
  const admin = false;
  const layout = admin ? 'custom' : 'default';
</script>
