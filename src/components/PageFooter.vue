<template>
  <footer class="footer">
    <div class="footer__columns">
      <!-- 1ая колонка -->
      <div class="footer__column footer__column_content_copyright">
        <p class="footer__author">&copy; Павел Черданцев</p>
      </div>

      <!-- 2ая колонка -->
      <nav class="footer__column footer__column_content_info">
        <h2 class="footer__column-heading">Другие проекты</h2>
        <ul class="footer__column-links">
          <li>
            <a
              href="https://chepash.github.io/mesto-react/"
              class="footer__column-link"
              >Проект "Место"</a
            >
          </li>
          <li>
            <a
              href="https://chepash.github.io/russian-travel/"
              class="footer__column-link"
              >Путешествия</a
            >
          </li>
          <li>
            <a
              href="https://chepamovies.nomoredomains.monster/"
              class="footer__column-link"
              >Сайт-портфолио</a
            >
          </li>
        </ul>
      </nav>

      <!-- 3я колонка -->
      <nav class="footer__column footer__column_content_social">
        <h2 class="footer__column-heading">Соцсети</h2>
        <ul class="footer__column-links">
          <li>
            <a href="https://www.facebook.com/" class="footer__column-link">
              <img
                class="footer__social-icon"
                src="../assets/logo_social/facebook_color_white.svg"
                alt="Фэйсбук"
              />
              Facebook
            </a>
          </li>
          <li>
            <a href="https://www.instagram.com" class="footer__column-link">
              <img
                class="footer__social-icon"
                src="../assets/logo_social/instagram_color_white.svg"
                alt="Инстаграм"
              />
              Instagram
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {
  name: "PageFooter",
};
</script>
