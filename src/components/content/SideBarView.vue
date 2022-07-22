<template>
<div class="siderbar">
    <Form></Form>
</div>
</template>

<script>
import Form from './FormView.vue';
export default {
    components:{
        Form,
    }
}
</script>

<style>
    .siderbar{
        width: 30%;
        margin-top: 12px;
    }
</style>