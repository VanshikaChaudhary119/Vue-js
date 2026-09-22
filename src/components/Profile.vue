<template>
    <h1>{{ profile }}'s Profile page</h1>
<!-- <h2>{{$route.params.name}}'s Profile page</h2> -->
</template>

<script>
import { useRoute } from 'vue-router'
export default{
    data()
    {
        return{
            profile:'',
        }
    },
mounted()
{
    const route = useRoute();
    console.warn("route", route.params.name);
    this.profile=route.params.name;
}
}
</script>