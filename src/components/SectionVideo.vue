<template>
  <section class="video">
    <h2 class="section-title video__section-title">Видео нa TED</h2>
    <p class="section-subtitle">Для тех, кто любит прокрастинировать</p>

    <div class="video__iframes">
      <iframe
        class="video__iframe"
        src="https://www.youtube.com/embed/5MgBikgcWnY"
        title="The first 20 hours -- how to learn anything | Josh Kaufman | TEDxCSU"
        allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      >
      </iframe>

      <iframe
        class="video__iframe"
        src="https://www.youtube.com/embed/arj7oStGLkU"
        title="Tim Urban: Inside the mind of a master procrastinator | TED"
        allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      >
      </iframe>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionVideo",
};
</script>
