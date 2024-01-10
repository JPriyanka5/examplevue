<script>
export default{
  data(){
    return{
     name:" ",
     email:" ",
     }
  }
}
</script>

<template>
  <h1>Login page</h1>
  <div class="register">
    <input type="text" placeholder="Name" v-model="name" ><br>
    <input type="email" placeholder="Email" v-model="email"><br>
    <input type="password" placeholder="password"><br>
    <button @submit=" ">login</button>
  </div>
  <p>{{name}} {{email}}</p>
</template>
<style>
h1{
  text-align:center;
  }
.register{
  text-align:center;
  margin-bottom:10%;
  }
</style>