<template>
  <div class="social">
    <form class="form" action="#">
      <div class="form-group">
        <input class="form-input" type="text" placeholder="Updates in your inbox..." pattern="[A-Za-z]{15}">
        <button class="btn" type="submit">GO</button>
      </div>
    </form>
    <ul class="list">
      <li class="item">
        <a href="#" class="link">Home</a>
      </li>
      <li class="item">
        <a href="#" class="link">Pricing</a>
      </li>
      <li class="item">
        <a href="#" class="link">Products</a>
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
      <li class="item">
        <a href="#" class="link">Privacy Policy</a>
      </li>
    </ul>
    <div class="images">
      <img class="image" src="@/assets/images/icon-facebook.svg" alt="Facebook">
      <img class="image" src="@/assets/images/icon-youtube.svg" alt="YouTube">
      <img class="image" src="@/assets/images/icon-twitter.svg" alt="Twitter">
      <img class="image" src="@/assets/images/icon-pinterest.svg" alt="Pinterest">
      <img class="image" src="@/assets/images/icon-instagram.svg" alt="Instagram">
    </div>
    <div class="logo">
      <img class="image" src="@/assets/images/logo-white.svg" alt="manage">
    </div>
    <div class="copy-right">
      <span class="c-r">Copyright 2020. All Rights Reserved</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Social'
  }
</script>