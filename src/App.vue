<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <DescriptionCard 
      language-name="Javascript"
      image="https://www.javilazaro.es/wp-content/uploads/2019/02/Javascript-logo-basico-946x1024.png"
      description="JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. Read more about JavaScript."
    />
  </div>
</template>

<script>
import DescriptionCard from "./components/DescriptionCard.vue";

export default {
  name: 'App',
  components: {
    DescriptionCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
