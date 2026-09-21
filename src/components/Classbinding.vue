<template>
    <h1>Class binding</h1>
    <h2 :class="applyStyle">Home Component</h2>
    <button v-on:click="colorfull=!colorfull">Apply style</button>
</template>
<script>
export default{
    data()
    {
        return{
            colorfull:false
        }
    },
    computed:{
        applyStyle(){
            return{
                green:this.colorfull,
                err:true,
                other:true
            }
        }
    }
}
</script>
<style scoped>
h1{
    color:orange
}
.green{
    background-color: aqua;
    width:200px;
    padding:10px;
}
.err{
    color:red;
}
.other{
    font-size:20px;
}
</style>