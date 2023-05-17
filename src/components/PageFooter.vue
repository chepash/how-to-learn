<template>
  <footer class="footer">
    <div class="footer__columns">
      <!-- 1ая колонка -->
      <div class="footer__column footer__column_content_copyright">
        <a
          href="https://practicum.yandex.ru/"
          class="logo logo_place_footer"
        ></a>

        <p class="footer__author">&copy; Павел Черданцев</p>
      </div>

      <!-- 2ая колонка -->
      <nav class="footer__column footer__column_content_info">
        <h2 class="footer__column-heading">О Практикуме</h2>
        <ul class="footer__column-links">
          <li><a href="#" class="footer__column-link">Главная</a></li>
          <li><a href="#" class="footer__column-link">Концепция</a></li>
          <li><a href="#" class="footer__column-link">Наставники</a></li>
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
            <a href="https://vk.com/" class="footer__column-link">
              <img
                class="footer__social-icon"
                src="../assets/logo_social/vk_color_white.svg"
                alt="ВК"
              />
              Вкотнатке
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
