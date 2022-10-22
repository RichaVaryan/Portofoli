<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="greetings">
    <h1 class="green">Richa Varyan</h1>
    <h3>
      Student in <a href="https://www.unair.ac.id" target="_blank" rel="noopener">Airlangga Universiy</a> and participants of independent study program in
      <a href="https://stechoq.com" target="_blank" rel="noopener">PT STECHOQ Robotika Indonesia</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
