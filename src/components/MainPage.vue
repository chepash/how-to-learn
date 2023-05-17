<template>
  <div class="page">
    <PageHeader />

    <main class="content">
      <SectionDesription />
      <SectionTechniques />
      <SectionVideo />
      <SectionOakley />
      <SectionFeynman />
      <SectionDigits />
      <SectionKhan />
      <SectionKaufman />
      <SectionResources />
    </main>

    <PageFooter />
  </div>
</template>

<script>
import PageHeader from "./PageHeader.vue";
import PageFooter from "./PageFooter.vue";
import SectionDesription from "./SectionDesription.vue";
import SectionTechniques from "./SectionTechniques.vue";
import SectionVideo from "./SectionVideo.vue";
import SectionOakley from "./SectionOakley.vue";
import SectionFeynman from "./SectionFeynman.vue";
import SectionDigits from "./SectionDigits.vue";
import SectionKhan from "./SectionKhan.vue";
import SectionKaufman from "./SectionKaufman.vue";
import SectionResources from "./SectionResources.vue";

export default {
  name: "MainPage",
  components: {
    PageHeader,
    PageFooter,
    SectionDesription,
    SectionTechniques,
    SectionVideo,
    SectionOakley,
    SectionFeynman,
    SectionDigits,
    SectionKhan,
    SectionKaufman,
    SectionResources,
  },
  props: {
    msg: String,
  },
};
</script>
