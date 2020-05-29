<template>
  <el-dropdown class="user-actions-dropdown">
    <span class="el-dropdown-link ">
      <span class="user-actions-dropdown__icon icon-contacts"></span>
      James Cameron
      <i class="el-icon-arrow-down el-icon--right"></i>
    </span>
    <el-dropdown-menu slot="dropdown">
      <el-dropdown-item>Action 1</el-dropdown-item>
      <el-dropdown-item>Action 2</el-dropdown-item>
      <el-dropdown-item>Action 3</el-dropdown-item>
      <el-dropdown-item disabled>Action 4</el-dropdown-item>
      <el-dropdown-item divided>Action 5</el-dropdown-item>
    </el-dropdown-menu>
  </el-dropdown>
</template>

<script>
export default {
  name: "UserActionDropdown",
};
</script>

<style lang="scss" scoped>
.user-actions-dropdown {
  &__icon {
    margin-right: 16px;
  }
  .el-dropdown-link {
    cursor: pointer;
    color: var(--dark-color-primary);
    &:hover {
      color: var(--red);
    }
  }
}
</style>
