<template>
  <div class="hello">
    <p>{{ msg }}</p>
    <p>
      Plus d'informations sur
      <a href="https://geoservices.ign.fr/documentation/services/api-et-services-ogc/isochrones">
        le portail des géoservices de l'IGN
      </a>
    </p>
  </div>
</template>

<script>
export default {
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
