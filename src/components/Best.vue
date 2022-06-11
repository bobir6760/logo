<template>
  <div class="best">
    <div class="container">
      <div class="best-wrapper">
        <div class="best-info">
          <div class="best-info__image">
            <img src="@/assets/img/Ellipse13.svg" alt="" />
          </div>
          <div class="best-info__title">We are lOREM IPSUM</div>
          <div class="best-info__subtitle">
            Lorem Ipsum is simply dummy text of the printing and
            <br />typesetting industry. Lorem Ipsum has been the industry's
            <br />
            standard dummy text ever since the 1500s,
          </div>
        </div>
        <div class="best-item__image">
          <img src="@/assets/img/money.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Best",
};
</script>

<style lang="scss" scoped>
.best {
  padding: 50px 0px;
}
.best-wrapper {
  display: flex;
  align-items: center;
}
.best-info {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.best-info__image {
  width: 100%;
  cursor: pointer;
}
.best-info__title {
  font-size: 25px;
  text-transform: uppercase;
  font-weight: bold;
  cursor: pointer;
}
.best-info__subtitle {
  font-size: 18px;
}
.best-item__image img {
  width: 100%;
  cursor: pointer;
}
@media screen and (max-width: 992px) {
  .best-info__title {
    font-size: 20px;
  }
  .best-info__subtitle {
    font-size: 15px;
  }
}
@media screen and (max-width: 768px) {
  .best-wrapper {
    display: flex;
    flex-direction: column;
  }
}
@media screen and (max-width: 576px) {
  .best-info__title {
    font-size: 18px;
  }
  .best-info__subtitle {
    font-size: 12px;
  }
}
</style>
