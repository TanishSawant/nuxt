<template>
  <div class="box">
      <p>{{title}}</p>
      <p>{{description}}</p>
  </div>
</template>

<script>
export default {
    props: ['title', 'description']
}
</script>

<style>
    p {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
    }
</style>