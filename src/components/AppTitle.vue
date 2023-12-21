<script>
export default {
    name: 'titleComponent',
    data() {
        return{
            title: "La mia prima app con Vite!",
        }
    }
}
</script>

<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>