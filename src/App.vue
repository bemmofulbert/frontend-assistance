<template>
  <BackGround/>
  <heaDer/>
  <div id="messagerie_workSpace">
      <ConTacts/>
      <ChatSpace/>
  </div>
</template>

<script>
import BackGround from './components/consultant/background.vue'
import ConTacts from './components/consultant/contacts.vue'
import heaDer from './components/consultant/header.vue'
import ChatSpace from './components/consultant/chatSpace.vue'

export default {
  name: 'App',
  components: {
    BackGround,
    ConTacts,
    heaDer,
    ChatSpace
  }
}
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#messagerie_workSpace {
  display: flex;
  position: relative;
  top: 50px;
}
</style>
