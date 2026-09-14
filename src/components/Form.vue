<template>
<h1>Get input value</h1>
<input type="text" v-model="email">
<br>
<input type="text" v-model="password">

<button v-on:click="getData()" type="button">Get values</button>
</template>

<script>
export default {
    data()
    {
        return {
            email:null,
            password:null,
        }
    },
    methods:{
        getData()
        {
        console.warn("Function called",this.email,this.password);
        }
    }
}
</script>
<style>

</style>