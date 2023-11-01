<script setup>
import { ref } from 'vue'
import ChildComp from './TutorialStep12ChildComp.vue'

const greeting = ref('Hello from parent')
</script>

<template>
  <ChildComp :msg="greeting" />
</template>
