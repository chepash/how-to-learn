<template>
  <section class="techniques">
    <h2 class="section-title techniques__section-title">Техники обучения</h2>

    <p class="section-subtitle">Пять практик от Барбары Оакли</p>

    <ul class="cards">
      <li class="cards__item">
        <img
          class="cards__image"
          src="../assets/cards/cards-attention.png"
          alt="Книга и руки"
        />
        <h3 class="cards__title">Два вида внимания</h3>
        <p class="cards__description">
          Глубокие знания возникают, если чередовать сфокусированное и
          рассеянное мышление.
        </p>
      </li>
      <li class="cards__item">
        <img
          class="cards__image"
          src="../assets/cards/cards-recall.png"
          alt="Картинка сатуи"
        />
        <h3 class="cards__title">Recall</h3>
        <p class="cards__description">
          Вспоминайте изученное — это позволит соединить разрозненные порции
          памяти.
        </p>
      </li>
      <li class="cards__item">
        <img
          class="cards__image"
          src="../assets/cards/cards-interliving.png"
          alt="Много людей"
        />
        <h3 class="cards__title">Интерливинг</h3>
        <p class="cards__description">
          Изучайте несколько навыков одновременно, они обогащают друг друга.
        </p>
      </li>
      <li class="cards__item">
        <img
          class="cards__image"
          src="../assets/cards/cards-question.png"
          alt="Пустой хол"
        />
        <h3 class="cards__title">Вопросы</h3>
        <p class="cards__description">
          Слушая преподавателя, придумывайте хороший вопрос, который вас
          действительно волнует.
        </p>
      </li>
      <li class="cards__item">
        <img
          class="cards__image"
          src="../assets/cards/cards-competence.png"
          alt="Рука книги"
        />
        <h3 class="cards__title">Иллюзия компетентности</h3>
        <p class="cards__description">
          Повторите про себя, запишите, расскажите другу: вам только кажется,
          что вы владеете новой темой.
        </p>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: "SectionTechniques",
};
</script>
