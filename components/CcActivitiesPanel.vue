<template lang="html">
  <div class="wrap-panels">
    <div class="wrap-profile-panel">

      <ul id="profile-panel">

        <li class="item" id="item-social-media">
          <div><i class="fab fa-facebook-f"> </i> facebook</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

        <li class="item">
          <div><i class="fab fa-github"> </i> Github</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

        <li class="item">
          <div><i class="fab fa-gitkraken"> </i> GitKraken</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

        <li class="item">
          <div><i class="fas fa-basketball-ball"> </i> Dribbble</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

        <li class="item">
          <div><i class="fab fa-behance"></i> Behance</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

        <li class="item">
          <div><i class="fab fa-codepen"></i> Codepen</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

        <li class="item">
          <div><i class="fab fa-figma"> </i> Figma</div>
          <div><i class="fas fa-angle-right"></i></div>
        </li>

      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CcActivitiesPanel'
}
</script>

<style lang="css" scoped>

body{
  background:#f9f8fa;
}
#top-menu{
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

.fa-chess-knight{color:#12b886;}

i:hover{color:crimson;}
.wrap-panels .wrap-profile-panel #profile-panel{
  border-bottom:1px solid gray;
  border-right:1px solid gray;
  box-shadow: 0px 3px 3px #0001;
}
.wrap-panels .wrap-profile-panel #profile-panel .item {display:flex;border-bottom:1px solid lightgray;}
/* teste */
.wrap-panels .wrap-profile-panel #profile-panel {
    display: none;
    position: absolute;
    box-shadow: rgba(0, 0, 0, 0.133) 3px 3px 3px;
    color: black;
    width: 300px;
}
/*teste*/
.wrap-panels .wrap-profile-panel #profile-panel .item{
  background: white;
}
.wrap-panels .wrap-profile-panel #profile-panel .item:hover{background:#f1f2f3;}
.wrap-panels .wrap-profile-panel #profile-panel .item div{font-size:20px;}
.wrap-panels .wrap-profile-panel #profile-panel .item div:nth-child(1){width:100%; padding:5px 30px;}
.wrap-panels .wrap-profile-panel #profile-panel .item div:nth-child(2){width:auto;padding:5px 30px;}

</style>
