<template>
    <div>
        <b>Books List:</b>

        <hr/>

        <div v-for="book in props.books">
            <BookItem :book="book" :msg="msg"/>
        </div>
        
    </div>
</template>

<script setup>
import BookItem from './Bookitem.vue'

const props=defineProps(['books','msg'])


console.log(props)

</script>

<style  scoped>

</style>