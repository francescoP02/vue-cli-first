<template>
  <div class="jumbo">
    <span class="jumbo-text"
      >Questo è un Jumbotron, Lorem ipsum dolor sit amet consectetur adipisicing
      elit. Saepe sit nam autem unde laboriosam expedita quibusdam est quaerat
      veniam.
    </span>
  </div>
</template>

<script>
export default {
  name: "AppHero",
};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.jumbo {
  width: 80%;
  margin: 0 auto;
  height: 400px;
  background-image: url(../assets/pexels-rovenimagescom-949587.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
}

.jumbo-text {
  width: 20%;
  padding: 3rem;
  color: white;
}
</style>
