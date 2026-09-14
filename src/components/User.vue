<template>
<h1>{{ data.name }}</h1>
<h1>{{ data.email }}</h1>
<button v-on:click="getData(data.name)" >Alert Name</button>
</template>

<script>
export default{
    props:{
        data:Object,
        getData:Function
    },
   
}
</script>