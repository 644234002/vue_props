<template>
    <div>
        <b>{{ book.title }}</b><br/>
        {{ book.shortDescription }}<br/>
        {{ msg }}
        <hr/>

    </div>
</template>

<script setup>

//promp msg
const props=defineProps(['book','msg'])

const book=props.book
const msg=props.msg
//สร้างตัวแปร msg ที่รัค่า props ของ msg


</script>
<style  scoped>

</style>