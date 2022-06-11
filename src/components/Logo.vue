<template>
  <div class="logo">
    <div class="container">
      <div class="logo-wrapper">
        <div class="logo-wrapper__title">OUR EXCITING CLIENTS</div>
        <div class="logo-wrapper__image">
          <div class="logo-image">
            <img src="@/assets/img/LOGO.svg" alt="" />
          </div>
          <div class="logo-image">
            <img src="@/assets/img/LOGO.svg" alt="" />
          </div>
          <div class="logo-image">
            <img src="@/assets/img/LOGO.svg" alt="" />
          </div>
          <div class="logo-image">
            <img src="@/assets/img/LOGO.svg" alt="" />
          </div>
          <div class="logo-image">
            <img src="@/assets/img/LOGO.svg" alt="" />
          </div>
          <div class="logo-image">
            <img src="@/assets/img/LOGO.svg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Logo",
};
</script>

<style lang="scss" scoped>
.logo {
  padding: 50px 0px;
}
.logo-image img {
  width: 100%;
  cursor: pointer;
}
.logo-wrapper__image {
  display: flex;
  justify-content: space-between;
  gap: 50px;
  cursor: pointer;
}
.logo-wrapper__title {
  text-align: center;
  font-size: 30px;
  margin-bottom: 50px;
  cursor: pointer;
}
@media screen and (max-width: 768px) {
  .logo-wrapper__title {
    text-align: center;
    font-size: 20px;
    margin-bottom: 30px;
  }
}
@media screen and (max-width: 576px) {
  .logo-wrapper__image {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
  }
}
</style>
