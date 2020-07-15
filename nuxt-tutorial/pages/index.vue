<template>
  <section class="container">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <div>
      <app-logo/>
      <h1 class="title">
        Seguir Aprendiendo espñol....
      </h1>
      <p>con efrain y diego</p>
      <h2 class="subtitle">
        seleccione lo que desea abrir
      </h2>
      
      <div class="links">
        <a
          href="https://www.youtube.com/"
          class="button--green">YouTube</a>
        <a
          href="https://www.google.com"
          class="button--grey">Google</a>
        <a
          href="https://www.spanishdict.com/"
          target="_blank"
          class="button--blue">SpanDict</a>
        <div class="button--blue--add">
          <h3>+</h3>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  },
  data() {
    return {
    message : 'Escriba algo para traducir...',
    link : ''
    }
  },
  methods: {
    
  }
}
</script>

<style>
* {
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}

.input_123 {
  display: flex;
  margin-bottom: 15px;
}

.container {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 40px;
  color: #35495e;
  letter-spacing: 1px;
  animation: change-color 15s 3.5s;
}

.subtitle {
  font-weight: 300;
  font-size: 27px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  animation: change-color-sub 15s 1.5s;
}

.links {
  padding-top: 15px;
}

@keyframes change-color {
  from {color: #35495e;}
  to {color: rgb(202, 34, 5);}
}

@keyframes change-color-sub {
  from {color: #526488;}
  to {color: rgb(6, 128, 56);}
}
</style>

