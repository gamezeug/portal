<template>
  <div class="home">
    <nav class="navbar navbar-expand-lg">
      <a class="navbar-brand" href="#">
        <img src="../assets/icon.svg" height="70" alt="">
        <img src="../assets/logo.svg" alt="">
      </a>
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Overview</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#">Games</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link disabled" href="#">Tables</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#">Gamers</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#">Developers</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Log in</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#">Sign up</a>
        </li>
      </ul>
     
    </nav>
    <HelloWorld msg=""/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style>
.nav-link {
  color: #F3AD13;
}
</style>