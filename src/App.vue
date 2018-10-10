<template>
  <div id="app">
    <Exercise />
    <TacoBuilder msg="Build Tacos Below"/>
  </div>
</template>

<script>

import Exercise from './components/Exercise.vue'
import TacoBuilder from './components/TacoBuilder.vue'

export default {
  name: 'app',
  components: {
    Exercise,
    TacoBuilder
  }
}
</script>
