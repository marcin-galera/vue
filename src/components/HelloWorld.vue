<template>
 <h1 @click="changeName">{{name}}</h1>
</template>

<script>

export default {
  data() {
  return {
    name: 'Web'
  }
},
methods: {
changeName(){
  this.name === "Web" ? this.name = "Strona" : this.name = 'Web'
},
},
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
