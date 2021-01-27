<template>
    <form @submit.prevent="onSubmit">
        <input type="text" />
        <button type="submit">Create</button>
    </form>
</template>

<script>
export default {
    methods: {
        onSubmit() {
            
        }
    }
}
</script>

<style scoped>
    form {
        display: flex;
    }
    input {
        width: 100%;
    }
</style>