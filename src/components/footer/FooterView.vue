<template>
<footer>
    <FooterLeft/>
    <FooterRight/>
</footer>
</template>

<script>
import FooterRight from './FooterRight.vue';
import FooterLeft from './FooterLeft.vue';
export default {
    components:{
        FooterLeft,
        FooterRight
    }
}
</script>

<style>
    footer{
        display: flex;
        justify-content: space-between;  
    }
</style>