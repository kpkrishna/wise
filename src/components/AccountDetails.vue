<template>
  <div class="account-details is-left-aligned d-flex d-align-center">
    <el-dropdown class="account-details__dropdown ">
      <div class="account-details__dropdown__title">
        <span class="account-details__dropdown__icon d-flex">
          <span class="icon-ic_Bank_40px15x"
            ><span class="path1"></span><span class="path2"></span
            ><span class="path3"></span><span class="path4"></span
            ><span class="path5"></span><span class="path6"></span
          ></span>
        </span>
        <span class="el-dropdown-link">
          <p class="headerTitle18">
            Red Palo Alto
            <i class="el-icon-arrow-down el-icon--right"></i>
          </p>
          <span class="account-details__small-text">Checking ••• 774</span>
        </span>
      </div>
      <el-dropdown-menu slot="dropdown">
        <el-dropdown-item>Action 1</el-dropdown-item>
        <el-dropdown-item>Action 2</el-dropdown-item>
        <el-dropdown-item>Action 3</el-dropdown-item>
        <el-dropdown-item disabled>Action 4</el-dropdown-item>
        <el-dropdown-item divided>Action 5</el-dropdown-item>
      </el-dropdown-menu>
    </el-dropdown>
    <div class="account-details__divider"></div>
    <div class="account-details__available-balancce">
      <p class="headerTitle18">
        $1,450.00
      </p>
      <span class="account-details__small-text">Available balance</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "AccountDetails",
};
</script>

<style lang="scss" scoped>
.account-details {
  background-color: var(--light-grey);
  padding: 12px;
  border-radius: 36px 0 0 36px;
  height: 64px;
  &__dropdown {
    cursor: pointer;
    &__icon {
      font-size: 40px;
      margin-right: 12px;
    }
    &__title {
      display: flex;
      align-items: center;
      .el-dropdown-link {
        display: flex;
        // align-items: center;
        flex-direction: column;
      }
    }
  }
  &__small-text {
    display: block;
    font-size: 12px;
    line-height: 14px;
    font-weight: normal;
    color: var(--dark-color-7);
  }
  &__divider {
    background-color: var(--light-grey-1);
    margin: 0 24px;
    height: 100%;
    width: 1px;
    display: inline-block;
  }
  &.is-left-aligned {
    padding-right: 64px;
    margin-right: -64px;
  }
}
</style>
