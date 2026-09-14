<template>
<h1 v-if="show" >If condition </h1>
<h1 v-else>Else Condition</h1>
<button v-on:click="show=!show" >Toggle</button>
</template>

<script>
export default{
    data()
    {
        return{
            show:true
        }
    }
}
</script>