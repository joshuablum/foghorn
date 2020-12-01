<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Learn audio and whistle signals for sailors 🦭<br />
      <a
        href="https://github.com/joshuablum/foghorn"
        target="_blank"
        rel="noopener"
        >Check out the source code on GitHub</a
      >
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
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
  color: #fca311;
}
</style>
