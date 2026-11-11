<script>


</script>


<template>
<!--top bar-->
  <body>
  <div class="topBar">
    <img src="./components/icons/TUS_Emblem.png" alt="tus logo" class="logo">
 <img src="./components/icons/TUS_LOGO.png"alt="tus typefont" class="tusFont">
    <h2><b>CampusLink</b> </h2>
    <img src="./components/icons/topPattern.png"alt="tus branding" class="design">
  </div>

  <!--side bar -->
<div class="sideBar">
  <ul>
    <li><b>Home</b></li>
    <li><b>Activities</b></li>
    <li><b>Clubs</b></li>
    <li><b>Societies</b></li>
    <li><b>Calender</b></li>


  </ul>
<h3><b>Recent Updates:</b></h3>
</div>

<!-- bottom bar -->
  <div class="bottomBar">
    <div class="userBox">
      <img src="./components/icons/userIcon.png"alt="user">
<h2>Signed in as User</h2>
    </div>
    <img src="./components/icons/tusBlingual.png" alt="tusBilingual"class="textLogo">
  </div>

  </body>
</template>



<style>

body{
  margin:0;
  padding:0;
font-family:sans-serif;
}
.userBox{
  height:151px;
  width:309px;
  background-color:#C7B88C;
  color:white;
  display:flex;
  align-items:center;
  flex-direction: column;
}
.userBox img{
  height:60%;
padding-top:12px;
}

.bottomBar{
 background-color:black;
  height:151px;
  width:100%;
  justify-content: flex-end;
  display:flex;
}
.bottomBar .textLogo{
  max-width:50%;
  margin-left:auto;
  height:50%;
  padding-top: 40px;
  padding-right: 15px;
}

.bottomBar .icon{
  max-width:25%;
  height:25%;

  align-items: center;
}

.sideBar{
  width:309px;
  height: 677px;
  background-color:#BAAD81;
margin-top: -16px;
  background-image: url("./components/icons/waves.png");
  background-repeat: no-repeat;
  background-position: center 30px;
  background-size:100% 280px;
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
ul li{
  height: 10px;
  padding-top: 48px;
  margin-top: 0;
  font-size: 20pt;
  font-weight: 700;
  color: #352A1F;
  list-style: none;
}

.sideBar h3{
  margin-top:120px;
  text-align:center;
  color:white;
}

</style>