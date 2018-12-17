<template lang="html">
  <div id="wrap-main-nav">
    <ul class="flex">
      <li id="item-profile" class="item" onclick="
        document.getElementById('wrap-profile').style.display = 'block';
        document.getElementById('wrap-help').style.display = 'none';
        document.getElementById('wrap-members').style.display = 'none';
      ">
        <a href="#">Profile</a>
      </li>
      <li id="item-help" class="item" onclick="
        document.getElementById('wrap-profile').style.display = 'none';
        document.getElementById('wrap-help').style.display = 'block';
        document.getElementById('wrap-members').style.display = 'none';
      ">
        <a href="#">Help</a>
      </li>
      <li id="item-members" class="item" onclick="
        document.getElementById('wrap-profile').style.display = 'none';
        document.getElementById('wrap-help').style.display = 'none';
        document.getElementById('wrap-members').style.display = 'block';
      ">
        <a href="#">Members</a>
      </li>

    </ul>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
#wrap-main-nav{
  background: white;
  box-shadow: 0px 1px 1px silver;
}
#wrap-main-nav .item{
  text-align: center;
  border:none;
  text-transform: uppercase;
}
.item{
    font-size:18px;
    width: 100%;
    padding: 10px;
}
</style>
