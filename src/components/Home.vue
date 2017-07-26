<template>
  <div>
    <group title="cell demo">
      <cell title="VUX" value="cool" is-link></cell>
    </group>
    <tabbar>
      <tabbar-item selected link="/">
        <img slot="icon" src="../assets/logo.png">
        <span slot="label">Wechat</span>
      </tabbar-item>
      <tabbar-item show-dot link="/hello">
        <img slot="icon" src="../assets/vux_logo.png">
        <span slot="label">Message</span>
      </tabbar-item>
      <tabbar-item  >
        <img slot="icon" src="../assets/logo.png">
        <span slot="label">Explore</span>
      </tabbar-item>
      <tabbar-item badge="2">
        <img slot="icon" src="../assets/vux_logo.png">
        <span slot="label">News</span>
      </tabbar-item>
    </tabbar>
  </div>
</template>

<script>
import { Tabbar, TabbarItem, Group, Cell } from 'vux'

export default {
  components: {
    Tabbar,
    TabbarItem,
    Group,
    Cell
  }
}
</script>>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
