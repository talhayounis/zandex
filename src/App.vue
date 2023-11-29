

<template>
  <div>Talha's ToDo</div>
  <ItemList :Items="DataItems"></ItemList>
</template>

<script setup lang="ts">
import ItemList from "./components/items.component.vue";

const DataItems: any = [
  {
    id: 1,
    name: 'Coffee',
    completed: false
  },
  {
    id: 2,
    name: 'books',
    completed: false
  },
  {
    id: 1,
    name: 'Coffee',
    completed: false
  },
]

</script>

<style scoped>
</style>
