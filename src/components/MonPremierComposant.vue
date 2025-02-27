<script setup lang="ts">
const message = "Bienvenue dans mon premier composant Vue ! 🎉";
</script>

<template>
    <div class="mon-composant">
        <h2>{{ message }}</h2>
    </div>
</template>

<style scoped>
.mon-composant {
    padding: 20px;
    background-color: #f3f4f6;
    border-radius: 8px;
    text-align: center;
    font-size: 1.2rem;
}
</style>