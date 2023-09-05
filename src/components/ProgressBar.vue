<template>
  <div class="q-pa-md bg-grey-9 text-white">
    <q-linear-progress dark stripe rounded size="20px" :value="progress2" color="red" class="q-mt-sm" />
  </div>
</template>


<script setup>
  import { ref } from 'vue'
  const progress2 = ref(0)
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
  button {
    font-weight: bold;
  }
</style>
