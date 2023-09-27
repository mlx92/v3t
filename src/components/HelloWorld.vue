
<script setup lang="ts">
import { shallowReactive, isReactive } from 'vue'

defineProps<{
  msg: string
}>()


const o2: {foo: number} = { foo: 3 };

console.log(o2.foo);

let age:number = 24;


</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <div>sadfa</div>
  </div>
</template>

<style scoped>

</style>
