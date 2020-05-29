<template>
  <div>
    <el-container class="wise-app-container">
      <SideBar />
      <el-container>
        <el-main class="wise-app-main">
          <el-header
            class="wise-app-header d-flex d-content-between d-align-center"
          >
            <h4 class="headerTitle28">Cards</h4>
            <AccountDetails />
          </el-header>
          <AddCardBtn />
          <CardsList />
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import SideBar from "../components/SideBar";
import AccountDetails from "../components/AccountDetails";
import AddCardBtn from "../components/AddCardBtn";
import CardsList from "../components/cards/CardsList";
export default {
  name: "CardsPageView",
  components: {
    SideBar,
    AccountDetails,
    AddCardBtn,
    CardsList,
  },
};
</script>

<style lang="scss" scoped></style>
