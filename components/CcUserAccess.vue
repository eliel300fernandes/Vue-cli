<template lang="html">
  <CcUserLogin></CcUserLogin>
  <CcUserRegistration></CcUserRegistration>
  <CcUserResetPassword></CcUserResetPassword>
</template>

<script>
import CcUserRegistration from './CcUserRegistration.vue'
import CcUserLogin from './CcUserLogin.vue'
import CcUserResetPassword from './CcUserResetPassword.vue'

export default {
  name: 'CcAccess',
  components:{
    CcUserLogin,
    CcUserRegistration,
    CcUserResetPassword
  }
}
</script>

<style lang="css">
</style>
