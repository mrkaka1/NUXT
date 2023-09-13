<template>
<div>
    <p>{{ titulo }}</p>
    <button @click="mudarTag">Mudar</button>
</div>
</template>


<script>
export default {
    name: "titulo",
    data() {
        return {
            titulo: "Basquete"
        }
    },
    methods: {
        mudarTag() {
            this.titulo = "Tenis de Mesa"
        }
    },
}
</script>