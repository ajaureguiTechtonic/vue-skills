<template>
  <div class="about">
    <h1>Hello {{ their_name }}, This is an about page</h1>
    <p>Lorm ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempur incididunt</p>
  </div>
</template>

<script>
  export default {
    name: 'Skills',
    data() {
      return {
        their_name: this.$route.params.name
      }
    }
  }
</script>
