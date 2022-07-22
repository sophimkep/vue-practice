<template>
<div class="main">
    <Card></Card>
</div>
</template>

<script>
import Card from './CardView.vue';
export default {
    components:{
        Card,
    }
}
</script>

<style>
    .main{
        flex: 2;
        padding: 10px;
        margin-right: 10px;
    }
</style>