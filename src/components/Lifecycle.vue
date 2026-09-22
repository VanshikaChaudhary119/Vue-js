<template>
    <h1>beforeCreate and created {{ name }}</h1>
</template>
<script>
export default{
    data()
    {
        return{
name:"vanshika"
        }
    },
    beforeCreate()
    {
        alert("beforeCreated");
    },
    created()
    {
        this.name="Chaudhary";
        alert("created");
    }
}
</script>