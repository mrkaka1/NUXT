<template>
<div>
    <h1>Produtos {{ id }}    </h1>
</div>
</template>

<script setup>
    const  { id } = useRoute().params;

</script>