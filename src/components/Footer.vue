<template>
   <footer>
        <div>
            <p>Copyright &copy; 2020 Alex M. | Design by: <a href="https://github.com/AlexandrMisiuk" target="_blank" rel="noopener">Alex M.</a></p>
        </div>
        <div>
            <h3>Design With Happiness</h3>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer' 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer{
    display: flex;
    flex-flow: column nowrap;
}
h3 {
  margin: 1vh 0 2vh;
}
a {
  color: #42b983;
}
</style>
