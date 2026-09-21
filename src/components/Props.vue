<template>
    <h1>Props in vue js</h1>
    <Student :name="studentName"/>
    <Teacher :name="teacherName"/>

</template>
<script>
import Student from './Student.vue'
import Teacher from './Teacher.vue';
export default {
    data()
    {
        return{
            studentName:"vanshika",
            teacherName:"kanika"
        }
    },
components:{
    Student,
    Teacher
}
}
</script>