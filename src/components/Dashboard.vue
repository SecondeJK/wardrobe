<template>
  <div>
    <SuiContainer>
      <h1 is="sui-header">{{ msg }}</h1>
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
      msg: 'Wardrobe Name'
    }
  }
}
</script>

<style scoped>
</style>
