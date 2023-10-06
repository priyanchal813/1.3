<template>
  <div id="app">

    <main>
        <img alt="My image" src="./assets/image.jpeg">

      <section class="portfolio">
        <div class="portfolio-item">
          <h2>Project 1</h2>
          <p>Pass tasks</p>
        </div>

        <div class="portfolio-item">
          <h2>Project 2</h2>
          <p>Credit tasks</p>
        </div>

      </section>
      
      <section class="about">
        <h2>About Me</h2>
        <p>Hi!!! This is a portfolio website made by me for the web responsive task 1.3p.</p>
      </section>
      
    </main>

    <footer>
      <p>&copy; 2023 Priyanchal</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

header {
  background-color: #333;
  color: white;
  padding: 20px;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

.portfolio {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.portfolio-item {
  margin: 20px;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 5px;
  text-align: center;
}

.portfolio-item img {
  max-width: 100%;
}

.about {
  background-color: #f5f5f5;
  padding: 40px;
}

footer {
  background-color: #333;
  color: white;
  padding: 20px;
}
</style>
