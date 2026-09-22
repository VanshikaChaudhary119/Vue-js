<template>
    <h1>Slots in vue.js </h1>
    <Slotschild><h1>Code has been done</h1></Slotschild>
    <Slotschild><a href="#">Vanshika Chaudhary</a></Slotschild>
    <!-- <Slotschild></Slotschild> -->

    <Slotschild>
        <template v-slot:header>
            <h1>Peter</h1>
        </template>
    </Slotschild>

     <Slotschild>
        <template v-slot:main>
           <p>A vue js product</p>
        </template>
    </Slotschild>

     <Slotschild>
        <template v-slot:footer>
            <button>Buy now</button>
        </template>
    </Slotschild>
</template>


<script>

import Slotschild from './Slotschild.vue';

export default{
    components:{
        Slotschild
    }
}
</script>