<template>
  <div class="cards-list">
    <CardItem />
  </div>
</template>

<script>
import CardItem from "./CardItem";
export default {
  name: "CardsList",
  components: {
    CardItem,
  },
};
</script>

<style lang="scss" scoped></style>
