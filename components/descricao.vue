<template>
<div>
    <p>{{ description }}</p>
    <button @click="mudarNome">Clique Aqui</button>
</div>
</template>

<script>
export default {
    name: "descricao",
    data() {
        return {
            description: "Batata"
        }
    },
    mounted() {
        this.mudarNome()
    },
    methods: {
        mudarNome () {
            this.description = "Pão de Queijo"
        }
    },
    
}
</script>   