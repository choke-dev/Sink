<script setup>
</script>

<template>
  <NuxtLayout name="default">
    <!--
    <a
      class="w-full h-full max-w-[600px] mx-auto flex items-center justify-center [&_svg]:w-full"
      href="/"
      v-html="errorImage"
    />
    -->
    <h1>404</h1>
    <p>Page not found</p>
    <NuxtLink to="/">
      Go Home
    </NuxtLink>
  </NuxtLayout>
</template>
