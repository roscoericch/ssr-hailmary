<script setup lang="ts">
    import auth from '~/middleware/auth';
    definePageMeta({
        middleware:[auth]
    })
</script>

<template>
    <main>
        <h2>Home page</h2>
    </main>
</template>