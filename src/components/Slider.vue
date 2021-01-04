<template>
  <div class="slider">
    <div class="content">
      <h3 class="title">What they’ve said</h3>
    </div>
    <ul class="figures">
      <li id="slider-one" class="figure">
        <img class="image" src="@/assets/images/avatar-anisha.png" alt="Avatar Anisha">
        <h4 class="title">Anisha Li</h4>
        <p class="text">“Manage has supercharged our team’s workflow. The ability to maintain visibility on larger milestones at all times keeps everyone motivated.”</p>
      </li> 
      <li id="slider-two" class="figure">
        <img class="image" src="@/assets/images/avatar-ali.png" alt="Avatar Ali">
        <h4 class="title">Ali Bravo</h4>
        <p class="text">“We have been able to cancel so many other subscriptions since using Manage. There is no more cross-channel confusion and everyone is much more focused.”</p>
      </li> 
      <li id="slider-three" class="figure">
        <img class="image" src="@/assets/images/avatar-richard.png" alt="Avatar Richard">
        <h4 class="title">Richard Watts</h4>
        <p class="text">“Manage allows us to provide structure and process. It keeps us organized and focused. I can’t stop recommending them to everyone I talk to!”</p>
      </li> 
      <li id="slider-four" class="figure">
        <img class="image" src="@/assets/images/avatar-shanai.png" alt="Avatar Shanai">
        <h4 class="title">Shanai Gough</h4>
        <p class="text">“Their software allows us to track, manage and collaborate on our projects from anywhere. It keeps the whole team in-sync without being intrusive.”</p>
      </li>
    </ul>
    <ul class="checks" @click="toggle">
      <li class="check">
        <a class="radio" href="#slider-one"></a>
      </li>
      <li class="check">
        <a class="radio" href="#slider-two"></a>
      </li>
      <li class="check">
        <a class="radio" href="#slider-three"></a>
      </li>
      <li class="check">
        <a class="radio" href="#slider-four"></a>
      </li>
    </ul>
    <div class="box">
      <a class="btn" href="#">Get Started</a>
    </div>
  </div>
</template>

<script> 
  export default {
    name: 'Slider',
    methods: {
      toggle(e) {
        const $LIST  = e.target

        if($LIST) {
          $LIST.classList.add('active')
        } else {
          $LIST.classList.remove('active')
        }

        console.log(CLASS.length > 5)
      }
    }
  }
</script>