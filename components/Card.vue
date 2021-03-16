<template>
  <div class="card">
    <img class="card__img" src="../static/images/tomato.jpeg" alt="томат" />
    <div class="card__content">
      <h2 class="card__title">Помидоры сладкие</h2>
      <p class="card__description">
        Плоды среднего размера, сочные и мясистые, с плотной ярко-красной
        кожицей. Восхитительно ароматная и нежная мякоть обладает насыщенным
        сладким вкусом. Внешний вид сезонного товара может отличаться от
        представленного на фотографии.
      </p>
      <p class="card__item-price">150 руб.</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.card {
  display: flex;
  max-width: 995px;
  height: 300px;
  background: #ffffff;
  box-shadow: 0px 0px 1px rgba(12, 26, 75, 0.24),
    0px 3px 8px -1px rgba(50, 50, 71, 0.05);
  box-sizing: border-box;
  padding: 25px;
}

.card__img {
  width: 350px;
  height: 250px;
}

.card__content {
  margin-left: 50px;
}

.card__title {
  font-family: "Inter", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 1;
  color: #425466;
  margin-bottom: 20px;
  text-align: left;
}

.card__description {
  font-family: "Inter", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 1.33;
  color: #425466;
  text-align: left;
  margin-bottom: 20px;
}

.card__item-price {
  font-family: "Inter", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 1.35;
  color: #27272e;
  text-align: left;
}
</style>
