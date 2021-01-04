<template>
  <section class="section container">
    <About />
    <Slider />
  </section>
</template>

<script>
  import About from '@/components/About'
  import Slider from '@/components/Slider'

  export default {
    name: 'Section',
    components: {
      About, 
      Slider
    }
  }
</script>