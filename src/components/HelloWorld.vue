<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li><a href="https://twitter.com/junkpiano"><icon name="twitter" scale="2"></icon></a></li>
      <li><a href="https://github.com/yuchan"><icon name="github-alt" scale="2"></icon></a></li>
      <li><a href="https://blog.junkpiano.me/"><icon name="rss" scale="2"></icon></a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Hi!',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
  color: #000000;
}

a:hover {
  color: #42b983;
}

svg, img {
  -webkit-transition: -webkit-transform .8s ease-in-out;
          transition:         transform .8s ease-in-out;
}
svg:hover, img:hover {
  -webkit-transform: rotate(360deg);
          transform: rotate(360deg);
}
</style>
