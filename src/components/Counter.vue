<script>
export default{
    data(){
        return{
            count:0, // also called state
        }
    },
    methods:{
        increment(){
            this.count++
        },
        decrement()
        {
            this.count--
        }
    }
}
</script>
<template>
    <h1>Counter</h1>
    <div>
        <button @click="increment">Increase</button>
        <h3>{{count}}</h3>
        <button @click="decrement">Decrease</button>
    </div>

</template>
<style></style>