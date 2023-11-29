<template>
    <div>Item list</div>
    <ul v-for="data in Items":key="data.id">
        <li>{{ data.name }} - <input type="checkbox" v-model="data.completed"></li>
    </ul>
</template>

<script lang="ts">
defineProps<Items : any[]>();
</script>