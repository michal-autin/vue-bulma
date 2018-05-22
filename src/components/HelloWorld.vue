<template>
  <div>
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title is-1">Technology Review TODOs</h1>
          <h2 class="subtitle">my own list</h2>
        </div>
      </div>
    </section>
    <div class="columns">
      <div class="column">
        <div class="card">
          <div class="card-content">
            <h4 class="title">Frontend</h4>
            <ul>
              <li>Service Worker</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-content">
            <h4 class="title">Web (general)</h4>
            <ul>
              <li>PWA and React Native - check if it is possible</li>
            </ul>
          </div>
        </div>
  
      </div>
      <div class="column">3</div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
</style>
