<template>
  <div>
      <SuiMenu
      vertical=true,
      fixed='left'>
          <a class="item">
            <i class="home icon"></i>
            Home
          </a>
          <a class="item">
            <i class="plus square outline icon"></i>
            Add Item
          </a>
          <a class="item">
            <i class="cogs icon"></i>
            Settings
          </a>
          <a class="item">
            <i class="sign out alternate icon"></i>
            Logout
          </a>
      </SuiMenu>
  </div>
</template>

<script>
export default {
  name: 'Menu',
  data () {
    return {
      msg: 'Menu'
    }
  }
}
</script>

<style scoped>
</style>
