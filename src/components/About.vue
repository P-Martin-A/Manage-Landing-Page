<template>
  <div class="about">
    <div class="content">
      <h3 class="title">What’s different about Manage?</h3>
      <p class="text">Manage provides all the functionality your team needs, without the complexity. Our software is tailor-made for modern digital product teams.</p>
    </div>
    <Articles />
  </div>
</template> 

<script>
  import Articles from './Articles'

  export default {
  name: 'About',
  components: { 
    Articles 
  },
  }
</script>