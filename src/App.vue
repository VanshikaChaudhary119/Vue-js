<script>
import Counter from './components/Counter.vue';
import Data from './components/Data.vue';
import Form from './components/Form.vue';
import Home from './components/Home.vue';
import IfElse from './components/IfElse.vue';
import Loops from './components/Loops.vue';
import Radio from './components/Radio.vue';

export default {
  components:{
    // Counter,
    // Home
    // Form
    // Radio
    // IfElse
    // Loops
    Data
  },
}
</script>

<template>
  <h1>You did it!</h1>
 <Home/>
 <Counter/>
 <Form/>
 <Radio/>
 <IfElse/>
 <Loops/>
 <Data/>
</template>


<style scoped></style>
