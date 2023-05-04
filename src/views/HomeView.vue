<template>
  <div class="home">
    <h1>lv</h1>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" />

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',

  data () {
    return {

      info: '我我我我是是是是刘刘刘刘梦梦梦梦！！！！！！'
    }
  },
  components: {
    HelloWorld
  }
}
</script>
