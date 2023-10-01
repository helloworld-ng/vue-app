<script setup>
import SampleComponent from '../components/SampleComponent.vue'
</script>

<template>
  <div class="frame">
    <nav>
      <img alt="App logo" src="../assets/logo.svg" />
    </nav>
    <main>
      <Transition name="fade" appear>
      <div><SampleComponent /></div>
      </Transition>
    </main>
    <footer>
    </footer>
  </div>
</template>

<style scoped>
</style>