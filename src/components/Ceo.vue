<template>
  <div class="ceo">
    <div class="container">
      <div class="ceo-wrapper">
        <div class="ceo-info">
          <div class="ceo-info__item">
            <div class="ceo-info__image">
              <img src="@/assets/img/Ellipse 10.svg" alt="" />
            </div>
            <div class="ceo-info__text">
              <div class="ceo-info__title">HEADING 1</div>
              <div class="ceo-info__subtitle">
                Lorem Ipsum is simply dummy text of the printing and
                <br />typesetting industry. Lorem Ipsum has been the
                <br />industry's standard dummy text ever since the 1500s,
              </div>
            </div>
          </div>
          <div class="ceo-info__item">
            <div class="ceo-info__image">
              <img src="@/assets/img/Ellipse 10.svg" alt="" />
            </div>
            <div class="ceo-info__text">
              <div class="ceo-info__title">HEADING 2</div>
              <div class="ceo-info__subtitle">
                Lorem Ipsum is simply dummy text of the printing and
                <br />typesetting industry. Lorem Ipsum has been the
                <br />industry's standard dummy text ever since the 1500s,
              </div>
            </div>
          </div>
          <div class="ceo-info__item">
            <div class="ceo-info__image">
              <img src="@/assets/img/Ellipse 10.svg" alt="" />
            </div>
            <div class="ceo-info__text">
              <div class="ceo-info__title">HEADING 3</div>
              <div class="ceo-info__subtitle">
                Lorem Ipsum is simply dummy text of the printing and
                <br />typesetting industry. Lorem Ipsum has been the
                <br />industry's standard dummy text ever since the 1500s,
              </div>
            </div>
          </div>
        </div>
        <div class="ceo-body__image">
          <div class="ceo-wrapper__image">
            <img src="@/assets/img/Group.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Ceo",
};
</script>

<style lang="scss" scoped>
.ceo {
  padding: 50px 0px;
}
.ceo-wrapper {
  display: flex;
  justify-content: space-between;
}
.ceo-body__image {
  text-align: center;
}
.ceo-wrapper__image img {
  width: 70%;
  cursor: pointer;
}
.ceo-info__image img {
  object-fit: contain;
  width: 100px;
  height: 100px;
  cursor: pointer;
}
.ceo-info {
  display: flex;
  flex-direction: column;
  gap: 80px;
}
.ceo-info__item {
  display: flex;
  gap: 30px;
}
.ceo-info__text {
  display: flex;
  flex-direction: column;
  gap: 10px;
  cursor: pointer;
}
.ceo-info__title {
  font-size: 25px;
  font-weight: bold;
  cursor: pointer;
}
.ceo-info__title:hover {
  text-decoration: underline;
}
.ceo-info__subtitle {
  font-size: 18px;
}
.ceo-wrapper__block {
  padding: 10px;
  background: #f0eeee;
  border-radius: 10px;
}
.ceo-block__title {
  font-size: 14px;
  margin-bottom: 30px;
}
.ceo-block__subtitle {
  font-weight: bold;
  margin-bottom: 5px;
}
@media screen and (max-width: 1200px) {
  .ceo-info__title {
    font-size: 20px;
  }
  .ceo-info__subtitle {
    font-size: 15px;
  }
}
@media screen and (max-width: 992px) {
  .ceo-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 30px;
  }
}
@media screen and (max-width: 576px) {
  .ceo-info__title {
    font-size: 17px;
  }
  .ceo-info__subtitle {
    font-size: 12px;
  }
}
</style>
