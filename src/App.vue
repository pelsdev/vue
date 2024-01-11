<template>
  
  <div class="container">
    <Header title="My first Vue app" action="Get Started" color="lightblue" bgcolor="darkblue"/>
</div>
<div class="container">
    <Header title="To do" action="Add task"/>
  
</div>

</template>

<script>
import Header from './Header.vue'

    export default {
      name: 'App',
      components: {
        Header
      }
    }
</script>

<style>
#app {
text-align: center;
margin-top: 2rem;
}
.container {
  border: 0.1rem solid steelblue;
  padding: 2rem;
  max-width: 500px;
  margin: 20px auto;
}

</style>
