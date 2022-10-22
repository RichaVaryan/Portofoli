<script>
import Pict from "@/components/Base/MyPict.vue";
export default {
  name: "HomePage",
  components: {
    Pict,
  },
};
</script>

<template>
  <section>
    <h2>About</h2>
    <p>I am a student at Airlangga University and also a participant in an independent study program at PT Stechoq Robotics Indonesia. I live in Surabaya. have an interest in the field of editing design and technology.</p>
    <div class="grid-container">
      <h2>This is me</h2>
      <Pict />
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
