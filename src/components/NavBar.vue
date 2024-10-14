<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
<template>
    <img
    alt="Yelko Otsogabia"
    class="logo"
    src="@/assets/yelko-square.jpg"
    />
    <div class="navbar">
        <nav>
            <!-- <RouterLink to="/">Home</RouterLink> -->
            <!-- <RouterLink to="/about">About</RouterLink> -->
        </nav>
    </div>
</template>
<style scoped lang="scss">
.logo {
    width: 80vw;
    height: auto;
    max-width: 450px;
    max-height: 450px;
    border-radius: 2rem;
}

.navbar {
    flex-grow: 1;
}

nav {
    display: flex;
    gap: 15px;
}

a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

a:hover {
    color: #007bff;
}

@media (min-width: 1024px) {
    .logo {
        width: 50vw;
        height: auto;
        max-width: 450px;
        max-height: 450px;
    }
}

</style>