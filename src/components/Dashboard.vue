<template>
  <div>
    <SuiContainer>
              <SuiMenu
        vertical=true,
      fixed='left'>
          <a class="item">
            <i class="home icon"></i>
            My Wardrobe
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
      <div style="margin-left:230px; margin-top:20px">
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
      </div>
    </SuiContainer>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
  data () {
    return {
      msg: 'Wardrobe Name'
    }
  }
}
</script>

<style scoped>
</style>
