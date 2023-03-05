<script lang="ts" setup>
import AppBarDefault from "@/components/_cores/AppBarDefault.vue";
</script>
<template>
  <AppBarDefault />
  <v-main>
    <slot name="main-content"></slot>
  </v-main>
</template>
