<template>
  <div id="App">
    <Nav />

    <div class="auth-wrapper">
      <div class="auth-inner">
        <Login />
      </div>
    </div>
  </div>
</template>

<script>
  import Nav from './components/Nav.vue'
  import Home from './components/Home.vue'
  import Login from './components/Login.vue'
  import Register from './components/Register.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Home,
    Login,
    Register
  }
}
</script>
 
<style>
  @import url('https://fonts.googleapis.com/css?family=Fira+Sans:400,500,600,700,800');

  * {
    box-sizing:border-box;
  }

  body{
    background: #1C8EF9 !important;
    min-height: 100vh;
    display:flex;
    font-weight:400;
    font-family: 'Fira Sans', sans-serif;
  }

  h1,h2,h3,h4,h5,h6,label,span{
    font-weight: 500;
    forn-family: 'Fira Sans', sans-serif;
  }

  body,html,#app,#root,.auth-warpper{
    width:100%;
    height:100%;

  }
  #app{
    text-alig:center;
  }

  .navbar-light{
    background-color:#ffffff;
    box-shadow:0px 14px 80px rgba(34, 34, 58, 0.2);
  }

  .auth-wrapper{
    display:flex;
    justify-content: center;
    flex-direction:column;
    text-align: left;
    height: 1000px;  
  }

  .auth-inner{
    width:450px;
    margin:auto;
    background:#ffffff;
    box-shadow:0px 14px 80px rgba(34,35,58,0.2);
    padding: 40px 55px 45px 55px;
    border-radius: 15px;
    transition: all .3s; 
  }

  .auth-wrapper .form-control:focus {
    virder-color: #167bff;
    box-shadow: none;
  }

  .auth-wrapper h3 {
    text-align: center;
    margin: 0;
    line-height: 1;
    padding-bottom: 20px;
  }

  .custom-control-label{
    font-weight: 400;
  }

  .forget-password,
  .forget-password a{
    text-align: right;
    font-size: 13px;
    padding-top: 10px;
    color: #7f7d7d;
    margin:0;
  }

  .forget-password a{
    color: #167bff;
  }


</style>
