<template>
  <el-row class="tac side-nav-bar__body">
    <el-menu
      default-active="1"
      class="side-nav-bar__el-menu"
      @open="handleOpen"
      @close="handleClose"
    >
      <el-menu-item class="side-nav-bar__el-menu__item" index="1">
        <div class="side-nav-bar__el-menu__item__icon">
          <span class="icon icon-Overview-deselected15x"></span>
          <span class="icon-selected icon-overview-selected"
            ><span class="path1"></span><span class="path2"></span
            ><span class="path3"></span><span class="path4"></span
          ></span>
        </div>
        <span>Overview</span>
      </el-menu-item>
      <el-menu-item class="side-nav-bar__el-menu__item" index="2">
        <div class="side-nav-bar__el-menu__item__icon">
          <span class="icon icon-transactions"></span>
          <span class="icon-selected icon-Transaction-Selected15x"
            ><span class="path1"></span><span class="path2"></span
          ></span>
        </div>
        <span>Transactions</span>
      </el-menu-item>
      <el-menu-item class="side-nav-bar__el-menu__item" index="3">
        <div class="side-nav-bar__el-menu__item__icon">
          <span class="icon icon-contacts"></span>
          <span class="icon-selected icon-Contacts-selected15x"
            ><span class="path1"></span><span class="path2"></span
          ></span>
        </div>
        <span>Contacts</span>
      </el-menu-item>
      <el-menu-item class="side-nav-bar__el-menu__item" index="4">
        <div class="side-nav-bar__el-menu__item__icon">
          <span class="icon icon-cards"></span>
          <span class="icon-selected icon-Selected15x"
            ><span class="path1"></span><span class="path2"></span
          ></span>
        </div>
        <span>Cards</span>
      </el-menu-item>
      <el-menu-item class="side-nav-bar__el-menu__item" index="5">
        <div class="side-nav-bar__el-menu__item__icon">
          <span class="icon icon-invoices"></span>
          <span class="icon-selected icon-Invoice-Selected"
            ><span class="path1"></span><span class="path2"></span
          ></span>
        </div>
        <span>Invoices</span>
      </el-menu-item>
    </el-menu>
  </el-row>
</template>

<script>
export default {
  name: "NavBar",
  methods: {
    handleOpen(key, keyPath) {
      console.log(key, keyPath);
    },
    handleClose(key, keyPath) {
      console.log(key, keyPath);
    },
  },
};
</script>

<style lang="scss" scoped></style>
