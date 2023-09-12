<template>
    <div class="p-2 justify-center">
        <h3>{{ title }}</h3>
        <p class="text-coolgray" v-html="text"></p>
    </div>
</template>

<script lang="ts" setup>
defineProps<{
    title: string; 
    text: string;
    icon: string;
}>();
</script>