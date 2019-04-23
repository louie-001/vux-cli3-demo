<template>
  <group>
    <cell title="cell title" is-link/>

    <tabbar style="position: fixed">
      <tabbar-item>
        <span slot="label">wehat</span>
        <emotion slot="icon" is-gif>微笑</emotion>
      </tabbar-item>
      <tabbar-item>
        <span slot="label">message</span>
        <emotion slot="icon" is-gif>得意</emotion>
      </tabbar-item>
      <tabbar-item>
        <span slot="label">news</span>
        <emotion slot="icon" is-gif>鼓掌</emotion>
      </tabbar-item>
    </tabbar>
  </group>
</template>

<script>
import {
    Group,
    Cell,
    Tabbar,
    TabbarItem,
    WechatEmotion
} from 'vux'

export default {
  name: 'HelloWorld',
  components: {
      Group,
      Cell,
      Tabbar,
      TabbarItem,
      Emotion: WechatEmotion
  }
}
</script>
