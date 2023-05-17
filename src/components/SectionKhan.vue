<template>
  <section class="khan">
    <div class="khan__container">
      <p class="khan__author">Салман Хан</p>
      <h2 class="khan__title">Весь мир — школа</h2>
      <!-- Специально для цитат, где много текста, можно использовать <blockquote> -->
      <blockquote class="khan__quote">
        Страсть и новаторство Сала Хана меняют процесс обучения миллионов
        студентов по всему миру. Книгу «Весь мир — школа» нужно прочитать всем,
        кто занимается образованием — так учащиеся повсюду смогут получить
        навыки и знания, которые приносят успех в школе, карьере и жизни.
      </blockquote>
      <!-- Будет лучше использовать тег заголовка h3 для автора цитаты -->
      <h3 class="khan__quote-author">Джордж Лукас</h3>
      <p class="khan__quote-author-subline">Кинорежиссер, продюсер</p>
      <div class="khan__book-container">
        <img
          class="khan__book-pic"
          src="../assets/khan-book.jpg"
          alt="Обложка книги 'Весь мир — школа'"
        />
        <a href="#" class="khan__buy-link">Купить книгу &rarr;</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionKhan",
};
</script>
