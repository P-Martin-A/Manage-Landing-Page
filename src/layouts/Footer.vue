<template>
  <footer class="footer container">
    <Work />
    <Social />
  </footer>
</template>

<script>
  import Work from '@/components/Work'
  import Social from '@/components/Social'

  export default {
    name: 'Footer', 
    components: {
      Work,
      Social
    }
  }
</script>