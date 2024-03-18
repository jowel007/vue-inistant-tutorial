<template>
    <div>
        <ChildComponent :childname="parentname" :clickFunction="alertFunction"/>
    </div>
</template>


<script>

import ChildComponent from '../components/Child.vue'

export default {
    name:'ParentComponent',
    components:{
        ChildComponent
    }, 
    data(){
        return{
            parentname:"Write Code With Vue Js"
        }
    },
    methods:
    {
        alertFunction()
        {
            alert("this is alert");
        }
    }
}

</script>