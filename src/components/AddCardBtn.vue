<template>
  <div class="add-card-btn">
    <el-button
      plain
      type="primary el-button--block el-button--dotted el-button-outlined"
      >+ Add a card</el-button
    >
  </div>
</template>

<script>
export default {
  name: "AddCardBtn",
};
</script>

<style lang="scss" scoped>
.add-card-btn {
  .el-button {
    height: 64px;
    text-transform: capitalize;
    font-size: 14px;
    letter-spacing: 0.116667px;
    border-radius: 8px;
    font-weight: 500;
    margin-bottom: 40px;
    border: 1.8px dotted var(--red);
    background-color: transparent;
  }
}
</style>
