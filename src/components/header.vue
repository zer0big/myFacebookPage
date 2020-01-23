<template>
  <div class="body">
    <div class="header">
      <div class="fb_logo"></div>
      <span class="email">E-mail address</span>
      <span class="password">Password</span>
      <div class="input_details">
        <input type="text" class="email_input" />&emsp;
        <input type="password" class="password_input" />&emsp;
        <!-- <a href="">Forgot account?</a> -->
        <button type="button" class="login">Log in</button>
        <br />
        <a href="#" class="forgotpassword">Forgot password?</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  /* background-color: red; */
  background: linear-gradient(white);
  font-family: Arial, Helvetica, sans-serif;
}
.header {
  /* height: 82px;
  min-width: 980px;
  direction: ltr;
  display: block;
  background-color: #3b5998;
  background-image: linear-gradient(#4e69a2, #3b5998 50%);
  border-bottom: 1px solid #133783;
  min-height: 42px;
  position: relative;
  z-index: 1; */
  background-color: #3b5998;
  min-width: calc(100% + 0.5em);
  margin-top: -0.5em;
  margin-left: -0.5em;
  margin-right: -0.5em;
  min-height: 42px;
  height: 82px;
  border-bottom: 1px solid #133783;
}
.fb_logo {
  background-image: url(https://facebook.com/rsrc.php/v3/y4/r/gf6iHxsw8zm.png);
  background-position: 0 0;
  background-size: 100% 100%;
  margin-top: 28px;
  width: 170px;
  height: 33px;
  /* margin-left: 12em; */
  left: 180px;
  display: inline-block;
  background-repeat: no-repeat;
  font-family: inherit;
  position: absolute;
  line-height: 1.34;
}
.email {
  position: absolute;
  right: 490px;
  color: white;
  top: 2%;
  font-family: Helvetica, Arial, sans-serif;
  font-size: 12px;
}
.password {
  position: absolute;
  right: 350px;
  color: white;
  top: 2%;
  font-family: Helvetica, Arial, sans-serif;
  font-size: 12px;
}
.email_input {
  border-color: #1d2a5b;
  margin: 0;
  width: 142px;
  border: 1px solid black;
  border-radius: 0;
  padding: 3px;
  background-color: #fff;
  color: #1c1e21;
}
.password_input {
  border-color: #1d2a5b;
  margin: 0;
  width: 142px;
  border: 1px solid black;
  border-radius: 0;
  padding: 3px;
  background-color: #fff;
  color: #1c1e21;
}
.input_details {
  top: 5%;
  right: 180px;
  position: absolute;
}
.login {
  background: none;
  border: 1px solid darkblue;
  border-radius: 1px;
  color: white;
  font-weight: bold;
  height: 22px;
}
.forgotpassword {
  top: 5%;
  position: relative;
  left: 175px;
  color: #9cb4d8;
  font-weight: normal;
  font-family: Helvetica, Arial, sans-serif;
  font-size: 12px;
}
</style>