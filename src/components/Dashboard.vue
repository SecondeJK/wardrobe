<template>
  <div>
    <SuiContainer>
      <SuiSidebar
        visible=true
        width='wide'>
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
      </SuiSidebar>
      <h1 is="sui-header">My Wardrobe</h1>
      <sui-item-group divided>
        <sui-item>
          <sui-item-image size="tiny" src="/static/images/placeholder.png" />
          <sui-item-content vertical-align="middle">
            <sui-item-header href="javascript:void(0)">T-Shirt</sui-item-header>
          </sui-item-content>
        </sui-item>
        <sui-item>
          <sui-item-image size="tiny" src="/static/images/placeholder.png" />
          <sui-item-content vertical-align="middle">
            <sui-item-header href="javascript:void(0)">Jumper</sui-item-header>
          </sui-item-content>
        </sui-item>
        <sui-item>
          <sui-item-image size="tiny" src="/static/images/placeholder.png" />
          <sui-item-content vertical-align="middle">
            <sui-item-header href="javascript:void(0)">Jeans</sui-item-header>
          </sui-item-content>
        </sui-item>
      </sui-item-group>
    </SuiContainer>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
  data () {
    return {
      msg: 'My Wardrobe'
    }
  }
}
</script>

<style scoped>
</style>
