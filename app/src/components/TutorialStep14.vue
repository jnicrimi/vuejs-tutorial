<script setup>
import { ref } from 'vue'
import ChildComp from './ChildComp14.vue'

const msg = ref('from parent')
</script>

<template>
  <ChildComp>Message: {{ msg }}</ChildComp>
</template>
