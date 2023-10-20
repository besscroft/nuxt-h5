<script setup lang="ts">
const router = useRouter()
</script>

<template>
  <div h-24 w-full flex items-center justify-center space-x-4 z-10>
    <div cursor-pointer i="carbon-home" @click="router.push('/')" title="主页" />
    <a href="https://github.com/besscroft/Nuxt-H5" target="_blank" title="GitHub">
      <div i="carbon-logo-github" />
    </a>
    <DarkToggle />
  </div>
</template>

<style scoped>

</style>
