<template>
    <div class="text-white">
        <select v-model="selectedGenre" @change="$emit('filterGenre', selectedGenre)" class="form-select">
            <option value="0">Seleziona il genere</option>
            <option value="1">One</option>
            <option value="2">Two</option>
            <option value="3">Three</option>
        </select>
    </div>
</template>

<script>
export default {
    name: 'SearchByGenre',
    data(){
        return {
            selectedGenre: '0'
        }
    }
}

</script>

<style lang="scss" scoped>

</style>