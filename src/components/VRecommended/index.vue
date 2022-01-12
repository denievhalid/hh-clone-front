<template>
  <div class="recommended">
    <h2 class="recommended__title">Рекомендуем лично вам</h2>
    <div class="recommended__items">
      <div class="recommended__item recommended-item">
        <div class="recommended-item__vacancy">
          SEO-оптимизатор с навыками разработки на Wordpress
        </div>
        <div class="recommended-item__salary">от 100 000 руб.</div>
        <a class="recommended-item__company" href="">
          Цезарь Сателлит, Москва, Москва
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.recommended {
  max-width: 640px;
  width: 100%;

  &__title {
    font-size: 24px;
    font-weight: 700;
    margin-bottom: 22px;
  }

  .recommended-item {
    & > * {
      margin-top: 3px;
    }

    &__company {
      color: #959799;
      font-size: 12px;
      display: block;
    }

    &__vacancy {
      color: #303233;
      line-height: 20px;
    }
  }
}
</style>
