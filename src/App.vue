<template>
  
  <div class="container">
    <h1>
    My first Vue app
  </h1>
  <button>Add Task</button>
</div>

</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
text-align: center;
color: greenyellow;
margin-top: 2rem;
}
.container {
  border: 0.1rem solid steelblue;
  padding: 2rem;
  max-width: 500px;
  margin: auto;
}
button {
  padding: 10px 20px;
  font-size: 15px;
  background-color: seagreen;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
</style>
