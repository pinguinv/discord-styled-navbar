<script setup>
import SidebarIcon from './SidebarIcon.vue';
const icons = ['1','2','3','4'];

</script>

<template>
    <div class="fixed top-0 left-0 h-screen w-16 m-0
        flex flex-col 
        bg-gray-900 text-white shadow-lg ">
        <SidebarIcon v-for="icon in icons" :icon="icon" text="tooltip 💡"/>
    </div>
</template>

<style scoped>

</style>