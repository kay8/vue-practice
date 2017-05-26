<template>
  <div class="hello">
    <h1>{{msg}}</h1>
    Hello {{ $route.params.name }}
    <transition name="fade">
      <router-view></router-view>
    </transition>
  </div>
</template>

<script>
export default {
  name: 'FirstRoute',
  data () {
    return {
      msg: 'FirstRoute'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
