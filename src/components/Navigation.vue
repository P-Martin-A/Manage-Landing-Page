<template>
  <nav class="navigation">
    <img @click="toggle" class="image menu" src="@/assets/images/icon-hamburger.svg" alt="Menu">
    <img @click="toggle" class="image close" src="@/assets/images/icon-close.svg" alt="Close">
    <ul class="list">
      <li class="item"> 
        <a href="#" class="link">Pricing</a>
      </li>
      <li class="item">
        <a href="#" class="link">Product</a>
      </li>
      <li class="item">
        <a href="#" class="link">About Us</a>
      </li>
      <li class="item">
        <a href="#" class="link">Careers</a>
      </li>
      <li class="item">
        <a href="#" class="link">Community</a>
      </li>
    </ul>
    <div class="box">
      <a class="btn" href="#">Get Started</a>
    </div>
  </nav>
</template>

<script>
  export default {
    name: 'Navigation',
    methods: {
      toggle() {
        const $IMAGE = document.querySelector('.image'),
              $MENU  = document.querySelector('.menu'),
              $CLOSE = document.querySelector('.close'),
              $LIST  = document.querySelector('.list')

        if($IMAGE) {
          $MENU.classList.toggle('inactive')
          $CLOSE.classList.toggle('active')
          $LIST.classList.toggle('active')
        } 
        
      }
    }
  }
</script>