<template>
  <div class="root relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0">
      <div>
          <LazyTypeWriter/>
      </div>
      <div class="link">
          <a href="https://aryos.id/blog/">Wanna go to my Blog instead?</a>
      </div>
  </div>
</template>

<script>
import TypeWriter from '~/components/TypeWriter.vue'
export default {
    name: 'App',
    components: {
        TypeWriter
    }
}
</script>

<style>
#aryos {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.app {
    margin: 0;
    padding: 0;
    background-color: #202124;
}
.root {
    height: 90vh;
    display: flex;
    flex-direction: column;
    align-content: center;
    justify-content: flex-end;
    align-items: center;
}
.link a {
    color: #4e4bd2;
    text-decoration: none;
    font-family: monospace;
}
</style>
