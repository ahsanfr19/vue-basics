<template>
    <h3>Component</h3>
    <div>
        <slot name="topSlot"></slot>
    </div>
    <div>
        <slot name="bottomSlot"></slot>
        <new-world/>
    </div>

   
</template>

<script>
import Newworld from './Newworld.vue'
export default{
    components : {
        'new-world' : Newworld
    }
}
</script>

<style scoped>
    div {
        height: 30px;
        width: 50%;
        border: dotted black 1px;
        margin: 10px;
        padding: 10px;
        background-color: lightgreen;
        font-weight: bold;
    }
</style> 