<template>
  <div>
    <test-component/>
   <NuxtLink to="/">Home</NuxtLink>
  </div>
</template>

<script>
import testComponent from '../components/test-component.vue'

export default {
  layout: 'blog',
  components: { testComponent },
  name: 'about'
}
</script>
