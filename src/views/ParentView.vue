<template>
    <div>
        <h2>This is Parent Component</h2>
        <ChildComponent/>
    </div>
</template>


<script>

import ChildComponent from '../components/Child.vue'

export default {
    name:'ParentComponent',
    components:{
        ChildComponent
    }
}

</script>