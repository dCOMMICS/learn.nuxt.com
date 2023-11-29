
<script setup lang="ts">

const props = defineProps<{
    
    moduleValue?: boolean,

}>()
</script>

<template>
    <div>
        Hello Muthored
        <slot/>
    </div>
</template>