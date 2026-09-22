<template>
    <h1>Slots in vue.js </h1>
    <Slotschild><h1>Code has been done</h1></Slotschild>
    <Slotschild><a href="#">Vanshika Chaudhary</a></Slotschild>
    <Slotschild></Slotschild>
</template>

<script>

import Slotschild from './Slotschild.vue';

export default{
    components:{
        Slotschild
    }
}
</script>