<template>
<h1>Dynamic Component</h1>
<button @click="tab='Java'">Load java</button>
<button @click="tab='Node'">Load node</button>
<button @click="tab='Php'">Load php</button>

<component :is="tab" />

</template>

<script>
import Java from './Java.vue';
import Node from './Node.vue';
import Php from './Php.vue';

export default{
    components:{
        Java,Php,Node
    },
    data()
    {
        return{
            tab:'Java'
        }
    }
}
</script>