<script>
import BaseCard from "@/components/Base/CardComp.vue";
import BaseCardd from "@/components/Base/CardCompp.vue";
import BaseCarddd from "@/components/Base/CardComppp.vue";

export default {
  name: "HomePage",
  components: {
    BaseCard,
    BaseCardd,
    BaseCarddd,
  },
};
</script>

<template>
  <section>
    <h2>Project</h2>
    <p>Some of my project</p>
    <div class="grid-container">
      <BaseCard />
      <BaseCardd />
      <BaseCarddd />
    </div>
  </section>
</template>
