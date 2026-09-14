<template>
<h1>Loops in vue</h1>
<ul>
    <li v-for="item in technology":key="item" >
    {{ item }}
    </li>
</ul>

<ul>
    <li v-for="item in user":key="item" >
        Name is:{{ item.name }} and Email is :{{ item.email }}
    </li>
</ul>
</template>

<script>

export default{
    data()
    {
        return {
            technology:['java','php','node','html'],
            user:[
                {
                 name:"vanshika",
                 email:"vanshika@123"
                },
                  {
                 name:"anshika",
                 email:"anshika@123"
                },
                  {
                 name:"anshikaa",
                 email:"anshikaa@123"
                }
            ]
        }
       
    }
}
</script>