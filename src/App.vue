<script setup>
import { ref, onMounted, computed, watch } from 'vue'

// ref handles our state
// onMounted used for rendering our page / component. It will allow us to create a localStorage
// computed used to make things in-order and create an array
// watch, it will watch our references and update our local storage

// references
const todos = ref([])
const name = ref('')

const input_content = ref('')
const input_category = ref(null)
</script>

<template>
  <div>
    <h1>Hello World!</h1>
  </div>
</template>
