<template>
  <div>
    <div class="bg-landing">
      <h2 class="h2-landing">Nouveau site en construction.<br>Retrouvez-nous sur <a target="_blank" href="https://www.facebook.com/eglise1236"><span>Facebook</span></a>.</h2>
      <h2 class="h2-landing">
        Vous pouvez aussi donner sur <a target="_blank" href="https://www.paypal.me/saintescene"><span>PayPal</span></a>.
      </h2>
    </div>
    <img class="logo-landing" src="@/assets/logos/logo.png" alt="">
    <nuxt />
  </div>
</template>

<style>
.bg-landing {
  display: flex;
  height: 100vh;
  width: 100vw;
  flex-flow: column wrap;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: linear-gradient(155deg, #b14ef7, #68affd, #722ffb);
  background-size: 600% 600%;
  -webkit-animation: AnimationName 24s ease infinite;
  -moz-animation: AnimationName 24s ease infinite;
  animation: AnimationName 24s ease infinite;
  }
.h2-landing {
  color: white;
}
a, a:hover {
  color: #b14ef7;
}
.logo-landing {
  position: absolute;
  bottom: 0;
  right: 0;
  padding: 25px;
  width: 15vw;
  height: auto;
}
@-webkit-keyframes AnimationName {
    0%{background-position:81% 0%}
    50%{background-position:20% 100%}
    100%{background-position:81% 0%}
}
@-moz-keyframes AnimationName {
    0%{background-position:81% 0%}
    50%{background-position:20% 100%}
    100%{background-position:81% 0%}
}
@keyframes AnimationName {
    0%{background-position:81% 0%}
    50%{background-position:20% 100%}
    100%{background-position:81% 0%}
}
</style>
