<template>
  <div>
    <Header></Header>
    <Conent></Conent>
  </div>
</template>

<script setup lang="ts">
import { ref, reactive } from "vue";
import Header from "./header/index.vue";
import Conent from "./content/index.vue";
</script>

<style scoped lang="less"></style>
