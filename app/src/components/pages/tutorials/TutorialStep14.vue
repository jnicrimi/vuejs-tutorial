<script setup>
import { ref } from 'vue'
import ChildComp from './TutorialStep14ChildComp.vue'

const msg = ref('from parent')
</script>

<template>
  <ChildComp>Message: {{ msg }}</ChildComp>
</template>
