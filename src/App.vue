<template>
<div class="display">
  <Title />
  <Hero />
</div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue';
export default {
  name: 'App',
  components: {
    Title,
    Hero,
  }
}
</script>

<style>
  .display {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
</style>
