<template>

  <div>
    <div class="outer_label">
       <img class="inner_label login_logo" src="../assets/logo.png">
    </div>
    <div class="login_form">

        <div class='yhclass' >用户名：<Input v-model="value16" maxlength="10" show-word-limit placeholder="请输入用户名" style="width: 200px" /></div>

         <div class='yhclass' >密&nbsp;&nbsp;&nbsp;&nbsp;码：<Input v-model="value18" type="password" password placeholder="请输入密码" style="width: 200px" /></div>
    </div>
      <!-- <input type="text"  class="qxs-ic_user qxs-icon"  placeholder="用户名" v-model="userName"> -->
      <!-- <input type="text"  class="qxs-ic_password qxs-icon"  placeholder="密码" v-model="password"> -->
      <Button type="primary">登录</Button>

    </div>

</template>
<script>

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '用户登录'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.yhclass{
    line-height: 78px;
}
.qxs-ic_user{
    width: 200px;
    display: block;
    position: relative;
    padding: auto;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;
}
</style>
