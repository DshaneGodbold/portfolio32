<template>
  <div class="about">
    <MySkills />
    <NavBar/>
    <h1></h1>
  </div>
</template>

<script>
// @ is an alias to /src
import MySkills from '@/components/MySkills.vue'
import NavBar from '@/components/NavBar.vue';
export default {
  name: 'AboutView',
  components: {
    MySkills,
    NavBar
}
}
</script>