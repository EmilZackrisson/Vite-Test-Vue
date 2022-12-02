<script lang="ts" setup></script>
<template>
    <div class="card">
        <div class="card__header">
        <h2 class="card__title">{{ title }}</h2>
        <p class="card__subtitle">{{ subtitle }}</p>
        </div>
        <div class="card__body">
        </div>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            required: true,
        },
        subtitle: {
            type: String,
            required: true,
        },
    },
};
</script>

<style>
.card {
    background-color: #fff;
    border-radius: 0.5rem;
    box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
    overflow: hidden;
    transition: all 0.3s;
}
</style>