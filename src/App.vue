<template>
  <div>
    <v-header />
    <v-search-panel />
    <main class="inner">
      <v-my-events />
    </main>
  </div>
</template>

<script>
import VHeader from "./components/VHeader";
import VMyEvents from "./components/VMyEvents";
import VSearchPanel from "./components/VSearchPanel";

export default {
  components: { VHeader, VMyEvents, VSearchPanel },
  mounted() {
    document.title =
      "Работа в Москве, поиск персонала и публикация вакансий - hh.ru";
  },
};
</script>
