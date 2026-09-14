<template>
    <h1>
       Pass data to child component
    </h1>
    <Child name="vanshika"
    :user="user"
    :getData="getData"/>
</template>

<script>
import Child from './Child.vue';

export default{
    components:{
        Child
    },
    data()
    {
        return{
            user:{
                name:"Preter",
                email:"perter@gmail.com"
            }
        }
    },
            methods:{
                getData()
                {
                    alert("Hello world");
                }
            }
        
    
}
</script>
<style scoped>
h1{
    color:orange
}
</style>