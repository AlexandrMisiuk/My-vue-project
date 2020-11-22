<template>
  <div class="block">
    <h1>{{ msg }}</h1>
    <h3>
      In this page I show my knowledges in Vue.js. And  also I want tell about me.
    </h3>
    <p>
      I am a web developer from Ukraine. I really like this direction and I am sure that I will not stop at Front-end development, and now I am actively studying everything related to IT. I'm sure I can help anyone to create their own site, or improve it. I have experience in web development, and you can see some of my work in 
      <a href="https://github.com/AlexandrMisiuk" target="_blank" rel="noopener">my page on GitHub.</a>
    </p>
    <h3>
      <a href="https://github.com/AlexandrMisiuk?tab=repositories" target="_blank" rel="noopener">My GitHub Repositories</a>
      </h3>
    <ul class="gitRepos">
      <li><a href="https://github.com/AlexandrMisiuk/Exam-work" target="_blank" rel="noopener">Exam work</a></li>
      <li><a href="https://github.com/AlexandrMisiuk/Flexbox-landing-page" target="_blank" rel="noopener">Flexbox landing page</a></li>
      <li><a href="https://github.com/AlexandrMisiuk/CSS-Grid-landing-page" target="_blank" rel="noopener">CSS Grid landing page</a></li>
      <li><a href="https://github.com/AlexandrMisiuk/My-vue-project" target="_blank" rel="noopener">My vue project</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Block',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 1vh 0 0;
}
ul {
  display: flex;
  justify-content: space-evenly;
  flex-flow: row nowrap;
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
}
a {
  color: #42b983;
}
.gitRepos>li>a{
  display: block;
  color: #ffffff;
  background-color: #e84c3d;
  text-transform: uppercase;
  text-align: center;
  padding: 0.8vh 1vh;
  text-shadow: 0px 1px 3px #000000;
  text-decoration: none;
  box-shadow: 0px 1px 3px #000000;
  transition: all 0.2s 
  ease 0.05s;
}
.gitRepos>li>a:hover{
  transform: scale(1.05);
}
</style>
