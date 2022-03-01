<template>
<div>
  <Tutorial/>
  <NuxtLink to="/about">About</NuxtLink>
</div>
</template>

<script>

export default {
  layout: 'blog',
  name: 'IndexPage',
  head() {
      // Configurer les méta tags pour cette page
  }
}
</script>
