<template>
  <h1>Alexandria Duell</h1>
  <div id="links">
    <a href="https://github.com/duellal" target="blank">Github</a>
    <a href="https://www.linkedin.com/in/alexandria-duell/" target="blank">LinkedIn</a>
    <a href="https://docs.google.com/document/d/e/2PACX-1vQXqcpBmogmYxzdWDyFVSgJa9IWZpmJMYPfiG9U3OSBHfXR9edoZeswjbBEvVWuG31Gfemmy11Dbo8Z/pub" target="blank">Resume</a>
    <a href="">Email</a>
  </div>
  <Projects />
</template>

<script>
import Projects from './components/Projects.vue'
export default {
  name: 'Portfolio',
  components: {
    Projects,
  },
  data: () => {
    return {
    }
  }
}
</script>

<style>
body {
  text-align: center;
  background-color: black;
  color: white;
}

a {
  color: white;
  text-decoration: none;
  padding: 3%;
}

#app{
  padding-top: 3%;
}

#links {
  display: flex;
  justify-content: center;
}

</style>
