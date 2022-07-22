<template>
  <form>
    <div class="form-group">
        <InputVue typeOfinput="text" textLable="Email" class="form-controller"/>
    </div>
    <div class="form-group">
       <InputVue typeOfinput="password" textLable="Password" class="form-controller"/>
    </div>
    <div class="form-group">
      <button>Login</button>
    </div>
  </form>
</template>

<script>
import InputVue from "./InputView.vue";
export default {
  components: {
    InputVue,
  },
};
</script>

<style>
form{
    margin-left: 10px;
}
.form-group{
  padding: 0.5rem;
  width: 300px;
}
.form-controller{
  width: 100%;
  padding: 0.5rem;
}
button{
  border: none;
  border-radius: 50px;
  background: orange;
  padding: 0.5rem 1.5rem;
}
</style>
