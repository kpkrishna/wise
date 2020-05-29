<template>
  <el-aside class=" side-nav-bar" width="248px">
    <figure class="side-nav-bar__header">
      <img src="../assets/images/logos/wise/Primary.png" width="100" alt="" />
    </figure>
    <NavBar />
    <div class="side-nav-bar__footer">
      <UserActionDropdown />
    </div>
  </el-aside>
</template>

<script>
import NavBar from "./NavBar";
import UserActionDropdown from "./user/UserActionDropdown";
export default {
  name: "SideBar",
  components: {
    UserActionDropdown,
    NavBar,
  },
};
</script>

<style lang="scss" scoped></style>
