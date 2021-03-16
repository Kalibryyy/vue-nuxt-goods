<template>
  <div class="container">
    <Card />
  </div>
</template>

<script>
import Cover from "../components/Cover";
export default {
  components: { Cover },
  // methods: {
  //   Testst() {
  //     console.log("test & test");
  //   },
  // },
};
</script>

<style>
.container {
  margin: 0 auto;
  max-width: 1920px;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
</style>
