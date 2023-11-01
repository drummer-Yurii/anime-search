<template>
  <div class="app">
    <header>
      <h1>The<strong>Anime</strong>Database</h1>
    </header>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Fira Sans', sans-serif;
}

a {
  text-decoration: none;
}

header {
  padding-top: 50px;
  padding-bottom: 50px;

  h1 {
    color: #888;
    font-size: 42px;
    font-weight: 400;
    text-align: center;
    text-transform: uppercase;

    strong {
      color: #313131;
    }

    &:hover {
      color: #313131;
    }
  }
}
</style>
