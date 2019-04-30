<template>
  <div class='home'>
    <img alt='Vue logo' src='../assets/logo.png'>
    <MyComponent msg='Learning...'></MyComponent>
  </div>
</template>

<script>
// @ is an alias to /src
import MyComponent from '@/components/MyTest.vue';

export default {
  name: 'home',
  components: {
    MyComponent,
  },
};
</script>
