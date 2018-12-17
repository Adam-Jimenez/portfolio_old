<template>
  <div class="home">
    <div class="intro">
      <h1>Hi, I'm Adam.</h1>
      <h2>Software Engineer / Hacker</h2>
      <Button @click.native="viewWork">View my work <font-awesome-icon icon="coffee"/></Button>
    </div>
  </div>
</template>

<script>
import Button from './Button';

export default {
  name: 'Home',
  methods: {
    viewWork() {
      this.$router.push('/work');
    },
  },
  components: {
    Button,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 4em;
}
h1, h2 {
  font-weight: normal;
}
.home {
  width: 100%;
  height: 100%;
  background: url("../assets/bg2.jpg") no-repeat center center fixed;
  background-size: cover;
  color: white;
}
.intro {
  /* center div */
  position: absolute;
  display: inline-block;
  width: 800px;
  top: 20%;
  left: 0; right: 0;
  margin: auto;
  max-width:100%;
  max-height:100%;
  overflow: hidden;
}
</style>
