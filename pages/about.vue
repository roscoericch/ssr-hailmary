<script setup lang="ts">
    import auth from '~/middleware/auth';
    definePageMeta({
        layout: "custom",
        middleware: auth
    })
</script>

<template>
    <div class="text-red">
        text styling
    </div>
</template>