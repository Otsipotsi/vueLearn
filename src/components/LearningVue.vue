<template>
<div class="container">
  <h1 class="title">{{ title }}</h1>
  <p>Text content here.</p>
</div>
</template>

<script>
export default {
  name: 'Learning Vue',
  props: {
    msg: String,
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="scss" scoped>
$gutter: 32px;
$color: #5f4343;

.container {
  .title {
    color: $color;
    font-size: 40px;
    margin: 1rem 0 calc(#{$gutter} * 2) 0;
  }
}

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
