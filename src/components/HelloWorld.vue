<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>About Me</h2>
    <p>
      Hi, saya Zidan Abdallah Maulana Rahman, Saya dari Probolinggo,<br />
      Mahasiswa Universitas Nurul Jadid, Junior WEB Developer dan Teknisi Komputer
    </p>
    <h2>My Project</h2>
    <ul>
      <img alt="laptop" src="../assets/laptop.png" height="350" width="350" />
      |
      <img alt="laptoprusak" src="../assets/laptoprusak.png" height="350" width="350" />
    </ul>

    <ul></ul>

    <ul></ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
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
