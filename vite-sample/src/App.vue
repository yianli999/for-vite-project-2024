<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import { ref } from 'vue';

const num = ref(2);
function clickMe() {
  num.value++
}
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->
  <div id="app">
      {{num}}
      <button type="button" v-on:click="clickMe">點我</button>
  </div>
</template>

<style>
</style>
