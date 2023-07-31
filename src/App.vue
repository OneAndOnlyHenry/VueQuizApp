<script setup>
  import { ref, computed } from 'vue'

  const questions = ref([
      {
        question: 'What is Vue?',
        answer: 0,
        options: [
          'A framework',
          'A library',
          'A type of hat'
        ],
        selected: null
      },
      {
        question: 'What is Vuex used for?',
        answer: 2,
        options: [
          'Eating a delicious snack',
          'Viewing things',
          'State management'
        ],
        selected: null
      },
      {
        question: 'What is Vue Router?',
        answer: 1,
        options: [
          'An ice cream maker',
          'A routing library for Vue',
          'Burger sauce'
        ],
        selected: null
      }
  ])
</script>

<template>
  <h1>Hello, World!</h1>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}

body {
  background-color: #271c36;
  color: #FFF;
}
</style>
