<template>
<h1>Ref in vue js</h1>
<input type="text" ref="input">
<button v-on:click="getData">Click me</button>
</template>

<script>
export default{
    methods:{
        getData()
        {
            this.$refs.input.focus();
            let val = this.$refs.input.value;
            console.warn(val);
             this.$refs.input.style.color="red"
        }
    }
}

</script>