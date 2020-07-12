<template>
  <img src="https://mextalki.com/LogoForWeb2.png" alt="" width="1200" height="300">
</template>

<style>
  img{
    position: relative;
    left: 380px;
   animation: turn 0.5s linear forwards 3.5s;
  }

@keyframes turn {
  100% {
    transform: rotateX(0deg);
  }
}

@keyframes godown {
  100% {
    top: 180px;
  }
}

@keyframes goright {
  100% {
    left: 10px;
  }
}
</style>

