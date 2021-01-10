<template>
  <div>
    <Header />
  </div>
</template>

<script>
import Header from './Header.vue'
export default {
  name: 'HelloWorld',
  components: {
    Header,
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
  @import '../assets/css/header.css';
</style>
