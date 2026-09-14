<template>
<h1>Radio and checkbox values </h1>

<h3>Technology</h3>
<label for="java">Java</label>
<input type="checkbox" name="" v-model="technology" id="java" value="java">
<br>
<label for="php">Php</label>
<input type="checkbox" name="" v-model="technology" id="php" value="php">
<br>
<label for="node">Node</label>
<input type="checkbox" name="" v-model="technology" id="node" value="node">

<h3>Who I am</h3>

<label for="student">Student</label>
<input type="radio" v-model="designation" name="who" id="student" value="student">
<label for="developer">Developer</label>
<input type="radio" v-model="designation" name="who" id="developer" value="developer">

<br>
<h3>Selected Technology : {{ technology }}</h3>
<h3>I am : {{ designation }}</h3>
</template>

<script>
export default{
    data(){
return{
    technology:[],
    designation:null
}
    },
   
}
</script>