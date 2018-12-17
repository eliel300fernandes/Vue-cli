<template lang="html">
  <div>
    <CcTopMenu></CcTopMenu>
    <CcActivitiesPanel></CcActivitiesPanel>
  </div>
</template>

<script>
import CcTopMenu from './CcTopMenu.vue'
import CcActivitiesPanel from './CcActivitiesPanel.vue'

export default {
  name: 'CcHeader',
  components:{
    CcTopMenu,
    CcActivitiesPanel
  }
}
</script>

<style lang="css" scoped>
*{
  font-family: 'Roboto', sans-serif;
  list-style:none;
  text-decoration: none;
}

</style>
