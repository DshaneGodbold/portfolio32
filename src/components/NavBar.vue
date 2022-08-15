<template>
  <div>
<nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About Me</router-link> |
      <router-link to="/resume">Resume</router-link> |
    </nav>
<router-view/>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style>

</style>
