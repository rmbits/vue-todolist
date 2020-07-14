<template>
  <header class="header">
    <div id="nav">
      <nav class="navbar navbar-expand-sm navbar-light bg-light">
        <div class="container">
          <router-link class="navbar-brand" to="/">TodoList</router-link>
          <button class="navbar-toggler" type="button"
            data-toggle="collapse" data-target="#navbarsExample07"
            aria-controls="navbarsExample07" aria-expanded="false"
            aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarsExample07">
            <ul class="navbar-nav mr-auto">
              <li><router-link class="nav-link" to="/">Home</router-link></li>
              <li><router-link class="nav-link" to="/about">About</router-link></li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
  .header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }

  .header a {
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }
</style>

