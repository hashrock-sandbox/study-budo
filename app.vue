<style>
  html, body{
    height: 100vh;
    margin: 0;
    padding: 0;
  }
  body{
    background: #eee;
  }
  main{
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  h1{
    text-shadow: 1px 0 3px #000;
    color: white;
    max-width: 50%;
  }
</style>

<template>
  <main>
    <h1>{{msg}}</h1>
  </main>
</template>

<script>
module.exports = {
  replace: false,
  data: {
    msg: "Hello, World"
  }
}
</script>