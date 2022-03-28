<template>
  <div class="counter" :style="{ color: $store.state.colorCode }">
    {{ $store.state.counter }}
  </div>
  <br />
  <br />
  <br />
</template>

<script>
export default {
  name: "Counter",
};
</script>

<style scoped>
.counter {
  font-size: 4rem;
  font-weight: bold;
  margin-bottom: -20px;
}
</style>
