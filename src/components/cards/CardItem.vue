<template>
  <div>
    <div class="card-item d-flex d-align-center ">
      <figure class="card-item__image">
        <img
          src="../../assets/images/Assistant card@3x.png"
          width="312"
          alt=""
        />
      </figure>
      <div class="card-item__details">
        <el-tag type="primary el-tag--card-tag">Wise Card</el-tag>
        <h3 class="headerTitle32 card-name">Assistant’s Card</h3>
        <div class="recent-transacions">
          <h6 class="headerTitle16 header-title">Recent transactions</h6>
          <div class="d-flex d-align-center">
            <div class="recent-transacions__item">
              <p class="recent-transacions__item__title">CVS</p>
              <p class="recent-transacions__item__details">
                -$20.55 <span class="is-warning">Pending</span>
              </p>
            </div>
            <div class="recent-transacions__item">
              <p class="recent-transacions__item__title">Apple music</p>
              <p class="recent-transacions__item__details">
                -$9.99 <span class="is-default">10 May’20</span>
              </p>
            </div>
            <div class="recent-transacions__item">
              <p class="recent-transacions__item__title">ATM</p>
              <p class="recent-transacions__item__details">
                -$150.00 <span class="is-default">24 May’20</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="card-item d-flex d-align-center ">
      <figure class="card-item__image">
        <img src="../../assets/images/Virtual card@3x.png" width="312" alt="" />
      </figure>
      <div class="card-item__details">
        <el-tag type="info el-tag--card-tag">Virtual</el-tag>
        <h3 class="headerTitle32 card-name">Online Purchases</h3>
        <div class="recent-transacions">
          <h6 class="headerTitle16 header-title">Recent transactions</h6>
          <div class="d-flex d-align-center">
            <div class="recent-transacions__item">
              <p class="recent-transacions__item__title">Shopify</p>
              <p class="recent-transacions__item__details">
                -$1500.32 <span class="is-default">Today, 9:35 am</span>
              </p>
            </div>
            <div class="recent-transacions__item">
              <p class="recent-transacions__item__title">Amazon</p>
              <p class="recent-transacions__item__details">
                -$245.22 <span class="is-default">23 May’20</span>
              </p>
            </div>
            <div class="recent-transacions__item">
              <p class="recent-transacions__item__title">Refund from Walmart</p>
              <p class="recent-transacions__item__details">
                <span class="is-success">+$100.00</span>
                <span class="is-default">19 May’20</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardItem",
};
</script>

<style lang="scss" scoped></style>
