<template>
  <header class="header">
    <a href="https://practicum.yandex.ru/" class="logo logo_place_header"></a>

    <h1 class="header__title">Научиться учиться</h1>
    <p class="header__subtitle">
      Какие современные и эффективные подходы к обучению вы можете использовать
      в своей жизни?
      <a href="#" class="header__link">Узнать &rarr;</a>
    </p>

    <img
      class="header__main-illustration"
      src="../assets/header-image.png"
      alt="Картина Решетникова - Опять двойка. 1952 г."
    />
    <div class="header__square-pic rotation"></div>
  </header>
</template>

<script>
export default {
  name: "PageHeader",
};
</script>
