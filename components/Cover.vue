<template>
  <section class="cover">
    <div class="cover__container">
      <h1 class="cover__title">Найдется всё!</h1>
      <p class="cover__description">
        Самые важные вещи для качественной жизни. Ласковые коты, вкусные
        помидоры и умопомрачительные носки!
      </p>
      <nav class="cover__nav">
        <button class="cover__btn">Помидоры</button>
        <button class="cover__btn">Коты</button>
        <button class="cover__btn">Носки</button>
      </nav>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      testData: "privet",
    };
  },
};
</script>

<style scoped>
.cover {
  background: #18191f;
  max-width: 1920px;
  min-height: 650px;
}

.cover__container {
  max-width: 61%;
  margin: 0 auto;
  height: 650px;
  background-image: url("../static/images/creative-block.png");
  background-position: right;
  background-repeat: no-repeat;
}

@media screen and (max-width: 1440px) {
  .cover__container {
    max-width: 75%;
  }
}

@media screen and (max-width: 1280px) {
  .cover__container {
    max-width: 85%;
  }
}

.cover__title {
  font-family: "Inter", sans-serif;
  font-weight: 800;
  font-size: 72px;
  color: #fff;
  box-sizing: border-box;
  padding-top: 159px;
  line-height: 1.25;
}

.cover__description {
  font-family: "Inter", sans-serif;
  font-weight: 400;
  font-size: 18px;
  line-height: 1.8;
  color: #fff;
  max-width: 540px;
  margin-top: 50px;
}

.cover__nav {
  margin-top: 60px;
}

.cover__btn {
  background: linear-gradient(44.11deg, #10c6ff 15.75%, #9f06ff 84.63%);
  border-radius: 33px;
  width: 190px;
  height: 60px;
  margin-right: 20px;
  border: 0;
}

.cover__btn:focus {
  outline: none;
  border: 1px solid #59636c;
}

.cover__btn:hover {
  cursor: pointer;
  background: #2a65cc;
}

.cover__btn:active {
  background: #2a65cc;
}
</style>
