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
  name: 'NotFoundComponent',
  data () {
    return {
      msg: 'NotFoundComponent'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
