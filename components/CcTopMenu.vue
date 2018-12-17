


<template lang="html">


  <div id="top-menu">
      <ul>
        <li class="item">
          <span id="icon-menu" onclick="
          if(document.getElementById('profile-panel').style.display == 'none'){
              document.getElementById('profile-panel').style.display = 'block';
            }else{
              document.getElementById('profile-panel').style.display = 'none';
            }"><i class="fas fa-bars"></i></span>
        </li>
    <li class="item">
      <span id="logo-home">HOME</span>
    </li>
    <li class="item" id="item-logo"><i class="fas fa-chess-knight"></i> LOGO</li>
    <li class="item">ACCOUNT</li>
  </ul>
  </div>

</template>

<script>
export default {
  name: 'CcTopMenu'
}
</script>

<style lang="css">
*{
  color:darkslategray;
  font-family:'Roboto', sans-serif;
  list-style:none;
  padding:0px;
  margin:0px;
}
body{
  background:#f9f8fa;
}
#top-menu{
  border-bottom:1px solid lightgray;
  /*background:#f9f1fa;*/
  box-shadow:inset 0px 25px 25px white, inset 0px -1px  white;
}
#top-menu ul{
  display:flex;
}
#top-menu .item{
  width:100%;
  padding:10px;
  border-right:1px solid silver;
}
#top-menu .item:last-child{
  border-right:none;
}

#top-menu .item:nth-child(1){
  width:auto;
  text-align:center;
}
#top-menu .item:nth-child(2){
  width:80%;
  text-align:left;
}
#top-menu .item:nth-child(3){
  text-align:center;
  padding-left:30px;
}
#top-menu .item:nth-child(4){
  text-align:right;
  padding-right:20px;
}

#profile-panel{
  display:none;
}
</style>
