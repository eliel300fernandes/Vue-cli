<template lang="html">
  <div>

    <div id="wrap-main-nav">
      <CcMainNav></CcMainNav>
    </div>

    <div id="wrap-main-content">
      <CcProfile></CcProfile>
      <CcHelp></CcHelp>
      <CcMembers></CcMembers>
    </div>

    <div>
      <CcText></CcText>
    </div>

  </div>
</template>

<script>
// import components
import CcText from './CcText.vue'
import CcProfile from './CcProfile.vue'
import CcHelp from './CcHelp.vue'
import CcMembers from './CcMembers.vue'
import CcMainNav from './CcMainNav.vue'

export default {
  name: 'CcMain',
  components: {
    CcMainNav,
    CcText,
    CcProfile,
    CcHelp,
    CcMembers
  }
}
</script>

<style lang="css">
  #wrap-main-content{
    background: #f9f8fa;
    display:flex;
  }

  #wrap-profile,
  #wrap-members,
  #wrap-help{
    width:100%;
  }

  #wrap-help,
  #wrap-members{
    display:none;
  }

</style>
