<template>
    <main>
        <nav class="flex gap-4">
            <NuxtLink active-class="text-red-[500]" class="text" to="/">Home</NuxtLink>
            <NuxtLink active-class="text-red-[500]" to="/about">About</NuxtLink>
        </nav>
        <p>layout component</p>
        <slot />
    </main>
</template>