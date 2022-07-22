<template>
    <input :type="typeOfInput" :placeholder="textLable" >
</template>

<script>
export default {
    props:{
        typeOfInput : String,
        textLable : String,
    }
}
</script>

<style>

</style>