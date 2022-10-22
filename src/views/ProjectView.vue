<script>
import BaseCard from "@/components/Base/CardComp.vue";
import BaseCardd from "@/components/Base/CardCompp.vue";

export default {
  name: "HomePage",
  components: {
    BaseCard,
    BaseCardd,
  },
};
</script>

<template>
  <section>
    <h2>About</h2>
    <p>Hello, my name is Richa Varyan. Im from Surabya, Indonesia.</p>
    <div class="grid-container">
      <h2>My Projects</h2>
      <BaseCard />
      <BaseCardd />
    </div>
  </section>
</template>

<style lang="scss">
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;

  .grid-item {
    width: 100%;
    overflow: hidden;
    border: 1px solid grey;
    border-radius: 1rem;

    figcaption {
      padding: 0.25rem 1rem;
      text-align: center;
    }
  }

  .grid-img {
    width: 100%;
  }
}
</style>
