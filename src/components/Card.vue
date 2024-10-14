<template>
    <div class="card">
        <div class="card-header">
            <slot name="header"></slot>
        </div>
        <div class="card-body">
            <slot></slot>
        </div>
        <div class="card-footer">
            <slot name="footer"></slot>
        </div>
    </div>
</template>
<script setup lang="ts">
</script>
<style scoped>
.card {
    border: 1px solid #ddd;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.card-header, .card-footer {
    padding: 10px;
}

.card-body {
    padding: 10px;
}
</style>