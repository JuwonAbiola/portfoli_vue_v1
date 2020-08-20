<template>
  <div id="app">
    <div class="test">
        <nav class="navbar fixed-top navbar-light kl">
      <img class="centered" src="./assets/logo.svg"/>
    </nav>  
    <nav class="navbar fixed-bottom navbar-light kl">
      <div class="icon-bar">
      <a href="https://twitter.com/_jhayX" target="_blank">
            <img class="centered" width="50" src="./assets/twitter.svg"/>
      </a>
      <a href="https://linkedin.com/in/abiolaoluwa" target="_blank">
            <img class="centered" width="50" src="./assets/link.svg"/>
      </a>
      <a href="https://github.com/jhayX" target="_blank">
            <img class="centered" width="50" src="./assets/github.svg"/>
      </a>
      <a href="/cv.pdf" target="_blank">
            <img class="centered" width="50" src="./assets/cv.svg"/>
      </a>
    </div>
    </nav>
    <router-view/>
    </div>
    <vue-particles
      color="#0066F5"
      :particleOpacity="0.7"
      :particlesNumber="40"
      shapeType="circle"
      :particleSize="3"
      linesColor="#0066F5"
      :linesWidth="1"
      :lineLinked="true"
      :lineOpacity="0.4"
      :linesDistance="150"
      :moveSpeed="3"
      :hoverEffect="true"
      hoverMode="repulse"
      :clickEffect="true"
      clickMode="push">
    </vue-particles>
  </div>
</template>