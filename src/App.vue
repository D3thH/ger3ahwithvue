<template>
<chosing class="body"></chosing>
</template>

<script>

import chosing from './components/chosing.vue'

export default {
  name: 'App',
  components: {
    chosing
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

/* ================================== */

.body {
  margin: 0;
  text-align: center;
  font-family: 'Roboto', sans-serif;
  position: relative;
}


h1 {
  color: #66BFBF;
  font-size: 562.5%; /*100% = 16px  --- i want 90px so 90px/16 = 562.5% */
  margin: 50px auto 0 auto;
  font-family: 'Aguafina Script', cursive;
}

h2 {
  color: #66BFBF;
  font-size: 2.5rem;
  font-weight: normal;
}

h3 {
  color: #11999E;
}
a{
  color: #11999E;
}
.top-container {
  background-color: #3d4698;
  position: relative;

}
hr{
  border-style: none;
  border-top-style: dotted;
  border-color: rgb(184, 181, 181);
  border-width: 5px;
  width: 5%;
  margin: 100px auto; /*or 100px auto 100px auto*/
}
p{
  color: #40514E;
  font-family: 'Kaisei Tokumin', serif;
  font-size: 1.5rem;
}

label{
  font-size:4rem
}
.name{
  font-size: 4rem;
}
.text_input{
  margin: 13rem 0;
  padding: 10% 5%;
  font-size: 50px;
  border: 5px solid black;
}

.eeb_photo{

  width: 61rem;
  height: 50rem;
  object-fit: coverس;
  margin: 0;
  /* padding: 10% 0; */

}


.bottom-container {
  background-color: #162a4c;
  margin-top: 100px;
  margin-bottom: 0px;
  padding-top: 60px;
  padding-bottom: 30px;
}
.footer-link{
  margin: 0 30px;
  color: #11999E;
}
.skill-row{
  text-align: left;
  margin: 100px auto; /*or 100px auto 100px auto*/
  width: 50%;
  line-height: 2;
}
.top-cloud {
  position: absolute;
  right: 300px;
  top: 50px;
}

.buttom-cloud {
  position: absolute;
  left: 300px;
  bottom: 300px;
}
.computer-img{
  width: 15%;
  float: left;
  margin-right: 30px;
  border-radius: 100%;
}
.oud-img{
  float: right;
  width: 15%;
  margin-left: 30px;
  border-radius: 100%;
}
#hr-dawn-abet{
  margin-top: 300px;
}
.oud-row{
    position: relative;
     top: 100px;
    position: relative;
    top: 100px;
}

.oud-h3-position{
  position: relative;
  top: 100;
  right: 2px;
}
.coyright{
  color: #EAF6F6;
}
.btn {
  margin-bottom: 14rem;
  background: #124A89;
  background-image: -webkit-linear-gradient(top, #124A89, #21385E);
  background-image: -moz-linear-gradient(top, #124A89, #21385E);
  background-image: -ms-linear-gradient(top, #124A89, #21385E);
  background-image: -o-linear-gradient(top, #124A89, #21385E);
  background-image: -webkit-gradient(to bottom, #124A89, #21385E);
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
  color: #FFFFFF;
  font-family: Brush Script MT;
  font-size: 68px;
  font-weight: 100;
  padding: 40px;
  -webkit-box-shadow: 1px 1px 20px 0 #000000;
  -moz-box-shadow: 1px 1px 20px 0 #000000;
  box-shadow: 1px 1px 20px 0 #000000;
  text-shadow: 1px 1px 20px #000000;
  border: solid #337FED 1px;
  text-decoration: none;
  display: inline-block;
  cursor: pointer;
  text-align: center;
}

.btn:hover {
  border: solid #337FED 1px;
  background: #1E62D0;
  background-image: -webkit-linear-gradient(top, #1E62D0, #3D94F6);
  background-image: -moz-linear-gradient(top, #1E62D0, #3D94F6);
  background-image: -ms-linear-gradient(top, #1E62D0, #3D94F6);
  background-image: -o-linear-gradient(top, #1E62D0, #3D94F6);
  background-image: -webkit-gradient(to bottom, #1E62D0, #3D94F6);
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
  text-decoration: none;
}


/* ===================================== */

</style>
