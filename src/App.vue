<template>
  <div id="app">
    <!--<img alt="Vue logo" src="https://vuejs.org/images/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <h1>Anomalies and violations</h1>
<p>

<dl class="row" id="av-list">
  <dt class="col-sm-3 font-italic small text-black-50">01-02-2022 01:00:32 
  <b class="text-warning">A</b>
  </dt>  
<dd class="col-sm-9">
<span>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="12" height="12"><path fill="none" d="M0 0h24v24H0z"/><path d="M10 11V8l5 4-5 4v-3H1v-2h9zm-7.542 4h2.124A8.003 8.003 0 0 0 20 12 8 8 0 0 0 4.582 9H2.458C3.732 4.943 7.522 2 12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10c-4.478 0-8.268-2.943-9.542-7z" fill="rgba(110,110,110,1)"/></svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="16" height="16"><path fill="none" d="M0 0h24v24H0z"/><path d="M2 13h6v8H2v-8zM9 3h6v18H9V3zm7 5h6v13h-6V8z" fill="rgba(230,30,30,1)"/></svg>
<span class="small text-danger">3.5x</span>
</span><br>
<span>User <b class="text-danger">bruce3397@some.com</b></span>
  has logged-in 3.5 times higher than normal users in controller <b class="text-warning">dcsrv001</b></span> 
  


<!-- start here -->
<dt class="col-sm-3 font-italic small text-black-50">01-02-2022 01:00:32 
  <b class="text-warning">A</b>
  </dt>  
<dd class="col-sm-9">
<span>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="12" height="12"><path fill="none" d="M0 0h24v24H0z"/><path d="M10 11V8l5 4-5 4v-3H1v-2h9zm-7.542 4h2.124A8.003 8.003 0 0 0 20 12 8 8 0 0 0 4.582 9H2.458C3.732 4.943 7.522 2 12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10c-4.478 0-8.268-2.943-9.542-7z" fill="rgba(110,110,110,1)"/></svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="16" height="16"><path fill="none" d="M0 0h24v24H0z"/><path d="M2 13h6v8H2v-8zM9 3h6v18H9V3zm7 5h6v13h-6V8z" fill="rgba(240,190,100,1)"/></svg>
<span class="small text-warning">1.1x</span>
</span><br>
<span>User <b class="text-danger">bruce3397@some.com</b></span>
  has logged-in 1.5 times higher than normal users in controller <b class="text-warning">dcsrv003</b></span> 
<!-- end here -->
  

</dl>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  margin-top: 60px;
}

dt.col-sm-3 {
  font-size: 10px;
}

dd.col-sm-9 {
  font-size: 12px;
}
</style>
