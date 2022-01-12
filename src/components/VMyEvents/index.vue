<template>
  <div class="my-events">
    <h2 class="my-events__title">Мои события</h2>
    <ul class="my-events__list">
      <li class="my-events__item">
        <a href="" class="my-events__link event-link">
          <span class="event-link__left">Отклики и приглашения</span>
          <span class="event-link__right">1034</span>
        </a>
      </li>
      <li class="my-events__item">
        <a href="" class="my-events__link event-link">
          <span class="event-link__left">Просмотры резюме</span>
          <span class="event-link__right">298</span>
        </a>
      </li>
      <li class="my-events__item">
        <a href="" class="my-events__link event-link">
          <span class="event-link__left">Избранные вакансии</span>
          <span class="event-link__right">2</span>
        </a>
      </li>
      <li class="my-events__item">
        <a href="" class="my-events__link event-link">
          <span class="event-link__left">Автопоиски</span>
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.my-events {
  max-width: 290px;
  width: 100%;

  &__title {
    font-size: 24px;
    font-weight: 700;
    margin-bottom: 22px;
  }

  &__item {
    & + * {
      margin-top: 22px;
    }
  }

  &__link {
    display: flex;
    justify-content: space-between;
    color: #303233;
  }
}
</style>
