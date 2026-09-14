<template>
<h1>Reuse Component</h1>
<ul>
    <li v-for = "item in user":key=item  >
    <user :data="item" 
    :getData="getData" />
    </li>
</ul>
</template>

<script>
import User from './User.vue';

export default{
    components:{
        User
    },
     methods:{
        getData(name)
        {
            alert(name)
        }
    },
    data()
    {
        return{
         user:[
            {
                name:"vanhsika",
                email:"vanshika@gmail.com"
            },
            {
                name:"ritika",
                email:"ritika@gmail.com"
            },
            {
                name:"kanika",
                email:"kanika@gmail.com"
            }
         ]
        }
    },
  
}
</script>