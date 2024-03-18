<template>
    <div>
        <h3>Welcome to {{ childname }}</h3>
        <button v-on:click="clickFunction">click here</button>
    </div>
</template>


<script>
export default {
    name: 'ChildComponent',
    props:{
        childname: String,
        clickFunction: Function 
    }
}
</script>