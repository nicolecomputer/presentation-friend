<script setup lang="ts">
import { ref } from 'vue'
import './nametag.css'

const props = defineProps({
  name: {
    default: "Erin",
  },
})

</script>

<template>
  <div class="nametag">
   <h2>Hi my name is</h2>
   <h1> {{ props.name }}</h1>
   <h3>W1 '24</h3>
  </div>
</template>
