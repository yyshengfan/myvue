<template>
  <div>
    <Head></Head>
    <Flowplayer></Flowplayer>
    <Content></Content>
    <Foot></Foot>
    <Copywrite></Copywrite>
  </div>
  
</template>

<script>
import Head from './head';
import Content from './content';
import Copywrite from './copywrite';
import Foot from './foot';
import Flowplayer from './flowplayer';
export default {
  name: 'HelloWorld',
  components: {
    Head, Flowplayer, Content, Foot, Copywrite
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
