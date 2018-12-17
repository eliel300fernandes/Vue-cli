<template lang="html">
  <div class="wrap-content">
    <CcHeader></CcHeader>
    <CcMain></CcMain>
    <CcProfile></CcProfile>
    <CcMembers></CcMembers>

  </div>
</template>

<script>
// import components
import CcHeader from './components/CcHeader.vue'
import CcMain from './components/CcMain.vue'

export default {
  name: 'VueApp',
  components: {
    CcHeader,
    CcMain
  }
}
</script>

<style lang="css">
body{
  padding: 0px;
  margin:0px;
  list-style:none;
  text-decoration:none;
  background:#f9f8fa;
}
.flex{
  display: flex;
}
.flex div,
.flex li{
  margin: 0 auto;
}
.container{
  padding:10px 40px;
}
</style>
