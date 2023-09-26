<template>
  <div v-if="errorMessage" class="error">
    {{ errorMessage }}
  </div>
</template>

<script>
export default {
  props: ["errorMessage"],
};
</script>

<style scoped>
.error {
  color: #ff0062;
  margin-top: 10px;
  font-size: 0.7em;
  font-weight: bold;
}
</style>
