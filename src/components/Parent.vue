<template>
<h1>{{ childUser }}</h1>
<Children :getUser="getUserName"/>
</template>

<script>
import Children from './Children.vue';
export default {
    data()
    {
        return{
         childUser:""
        }
    },
    components:{
        Children
    },
    methods:{
        getUserName(name)
        {
            this.childUser=name
        }
    }
}
</script>