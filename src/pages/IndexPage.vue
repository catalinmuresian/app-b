<template>
  <q-page class="flex flex-center">
    <h1>APP - B</h1>
    <q-btn @click="handleBtn">nav to APP - A</q-btn>
  </q-page>
</template>

<script setup>
import {useRouter} from "vue-router";

const router = useRouter()
function handleBtn () {
  window.open('https://catalinmuresian.github.io/app-a/', '_blank');
}

</script>
