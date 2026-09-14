<template>
<h2>{{ name }}</h2>
<h3>{{ user.name }}</h3>
<h3>{{ user.email }}</h3>
<button v-on:click="getData()">Call function</button>
</template>

<script>
export default {
    props:{
        name:String,
        user:Object,
        getData:Function
    }
}
</script>