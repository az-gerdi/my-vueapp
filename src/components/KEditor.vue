<template>
  <div class="keditor">
    <div class="kemenu"></div>
  </div>
</template>

<script>
export default {
  name: "KEditor",
  props: {
    msg: String
  },
  data() {
    return {
      oDoc: null
    }
  },
  created() {},
  mounted() {},
  methodes: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.keditor {
  margin: 0 auto;
  display: grid;
  width: 600px;
}
.kemenu {
  background-color: antiquewhite;
  height: 30px;
}
.ketext {
  height: 400px;
  background-color: lavender;
}
</style>
