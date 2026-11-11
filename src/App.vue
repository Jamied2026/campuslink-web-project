<script>


</script>


<template>
<!--top bar-->
  <body>
  <div class="topBar">
    <img src="./components/icons/TUS_Emblem.png" alt="tus logo" class="logo">
 <img src="./components/icons/TUS_LOGO.png"alt="tus typefont" class="tusFont">
    <h2>CampusLink </h2>
    <img src="./components/icons/topPattern.png"alt="tus branding" class="design">
  </div>

  <!--side bar -->
<div class="sideBar">
  <ul>
    <li>Home</li>
    <li>Activities</li>
    <li>Clubs</li>
    <li>Societies</li>
    <li>Calender</li>


  </ul>
<h3>Recent Updates:</h3>
</div>
<!-- bottom bar -->
  <div class="bottomBar">
    <img src="./components/icons/instagramIcon.png" alt="instagram" class="icon">
    <img src="./components/icons/tusBlingual.png" alt="tusBilingual"class="textLogo">
  </div>
  </body>
</template>



<style>

body{
  margin:0;
  padding:0;

}

.bottomBar{
 background-color:black;
  height:151px;
  width:100%;
}
.bottomBar .textLogo{
  max-width:60%;
  height:60%;
}

.bottomBar .icon{
  max-width:25%;
  height:25%;
}

.sideBar{
  width:309px;
  height: 677px;
  background-color:#BAAD81;
margin-top: -16px;
}

.topBar{
  width:100%;
  height:117px;
  background-color:black;
  box-sizing: border-box;
  display:flex;
  align-items: center;
}
.topBar h1{
color:white;
}

.topBar h2{
  color:white;
margin:auto;

}

.topBar .design{
  height:100%;
  margin-left: auto;
}
.topBar .logo{
  padding:10px;
  width:auto;
  height:65px;
}
.topBar .tusFont{
  max-width:5%;
}



</style>