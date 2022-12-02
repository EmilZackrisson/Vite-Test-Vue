<script lang="ts" setup></script>
<template>
    <button @click="clickCount++">Klickad {{clickCount}} gånger</button>
    <button @click="(clickCount = 0)">Reset</button>
</template>

<script>
export default {
    data() {
        return {
            clickCount: 0,
        };
    },
};

</script>

<style>
    button{
        margin: 30px;
        color: blue;
    }
</style>