<template>
  <div>
    <input v-model="colorCode" placeholder="Enter color code" type="text" />
  </div>
</template>

<script>
export default {
  name: "ColorCodes",
  computed: {
    colorCode: {
      get() {
        return this.$store.state.colorCode;
      },
      set(newValue) {
        this.$store.dispatch("setColorCode", newValue);
      },
    },
  },
};
</script>

<style scoped></style>
