<template>
<h1>Send child to parent data component</h1>
<button v-on:click="getUser(userName)">Send user name</button>
</template>

<script>
   export default {
    data()
    {
        return{
            userName:"Peter"
        }
    },
    props:{
        getUser:Function
    }
   }
</script>