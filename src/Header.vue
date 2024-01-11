<template>
  <header>
    <h1 :style="{color: color}">{{ title }}</h1>
    <button @click="handleClick()" :style="{background: bgcolor}">{{ action }}</button>
  </header>

</template>

<script>
    export default {
    name: 'Header',
    props: {
      title: String,
      action: String,
      color: String,
      bgcolor: String
    },
    methods: {
        handleClick() {
          console.log("Button Clicked")
        }
    }
}

</script>

<style>
h1 {
  color: greenyellow;
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