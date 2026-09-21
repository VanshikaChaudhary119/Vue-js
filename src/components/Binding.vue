<template>
    <h1>{{ text }}</h1>
    <div v-html="tag"></div>
    <div v-html="tag2"></div>
</template>
<script>
export default {
    data()
    {
        return{
            text:"vanshika",
            tag:"<h1>Vanshika Chaudhary</h1>",
            tag2:"<h1>vanshika@gmail.com</h1>"
        }
    }
}
</script>