<template>
  <div class="about">
    <div class="about-heading">
      <h1 id="about-heading">About Me</h1>
    </div>
    <div class="about-body">
      <img alt="Picture of me" src="../assets/about-me-image.jpg" width="250" id="about-me-img">
      <p id="about-text">My name is Stephen and I work in Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</p>
    </div>
  </div>
</template>
<style scoped>
.about {
  display:grid;
  grid-template-columns: auto 700px auto;
  align-items: center;
}
.about-heading {
  grid-column: 1/4;
  text-align: center;
}
.about-body {
  grid-column:2/3;
}
#about-me-img {
    float: left;
    margin:0 20px 10px 0;
}
#about-text {
  text-align: left;
  margin-top:0;
}
</style>
