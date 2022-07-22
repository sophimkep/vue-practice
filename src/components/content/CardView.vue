<template>
  <div class="card" v-for="card of listOfCard" :key="card">
    <div class="card-title">
        <p class="post">{{card.title}}</p>
    </div>
    <div class="card-body">
        <p>{{card.body}}</p>
    </div>
  <Btn/>
  </div>
</template>

<script>
import Btn from './ButtonView.vue';
export default {
    components:{
        Btn,
    },
    data(){
        return {
            listOfCard : [
                {title:"Post 1", body: "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aliquid animi doloribus dignissimos"},
                {title:"Post 2", body: "Lorem ipsum dolor sit, amet consectetur adipisicing elit."},
            ],
        }
    }
}
</script>

<style>
    .card{
        padding: 1rem;
        line-height: 2rem;
        border-top: 3px solid #9c27b0;
        border-radius: 7px;
        margin-top: 10px;
        box-shadow: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;
    }
    .post{
        border-bottom: 1px solid purple;
    }
</style>