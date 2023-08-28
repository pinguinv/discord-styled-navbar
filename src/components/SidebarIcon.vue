<script setup>
    const { icon, text } = defineProps(['icon', 'text'])

</script>

<template>
    <div class="sidebar-icon group">
        {{ icon }}

        <span class="sidebar-tooltip group-hover:scale-100">
            {{ text }}
        </span>
    </div>
</template>