<template>
  <div class="servic">
    <div class="container">
      <div class="servic-wrapper">
        <div class="servic-info">
          <div class="servic-info__title">OUR SERVICES</div>
          <div class="servic-info__subtitle">
            Lorem Ipsum is simply dummy text of the printing and
            <br />typesetting industry. Lorem Ipsum has been the
            <br />industry's standard dummy text ever since the 1500s,
          </div>
        </div>
        <div class="servic-wrapper__item">
          <div class="servic-block">
            <div class="servic-wrapper__image">
              <img src="@/assets/img/wall1.svg" alt="" />
            </div>
            <div class="servic-item__title">HEADING 5</div>
            <div class="servic-item__subtitle">
              Lorem Ipsum is simply dummy <br />text of the printing and
              typesetting <br />industry. Lorem Ipsum has been the
              <br />industry's standard dummy text ever since the 1500s,
            </div>
          </div>
          <div class="servic-block">
            <div class="servic-wrapper__image">
              <img src="@/assets/img/wall2.svg" alt="" />
            </div>
            <div class="servic-item__title">HEADING 6</div>
            <div class="servic-item__subtitle">
              Lorem Ipsum is simply dummy <br />text of the printing and
              typesetting <br />industry. Lorem Ipsum has been the
              <br />industry's standard dummy text ever since the 1500s,
            </div>
          </div>
          <div class="servic-block">
            <div class="servic-wrapper__image">
              <img src="@/assets/img/wall1.svg" alt="" />
            </div>
            <div class="servic-item__title">HEADING 7</div>
            <div class="servic-item__subtitle">
              Lorem Ipsum is simply dummy <br />text of the printing and
              typesetting <br />industry. Lorem Ipsum has been the
              <br />industry's standard dummy text ever since the 1500s,
            </div>
          </div>
          <div class="servic-block">
            <div class="servic-wrapper__image">
              <img src="@/assets/img/wall1.svg" alt="" />
            </div>
            <div class="servic-item__title">HEADING 8</div>
            <div class="servic-item__subtitle">
              Lorem Ipsum is simply dummy <br />text of the printing and
              typesetting <br />industry. Lorem Ipsum has been the
              <br />industry's standard dummy text ever since the 1500s,
            </div>
          </div>
          <div class="servic-block">
            <div class="servic-wrapper__image">
              <img src="@/assets/img/wall1.svg" alt="" />
            </div>
            <div class="servic-item__title">HEADING 9</div>
            <div class="servic-item__subtitle">
              Lorem Ipsum is simply dummy <br />text of the printing and
              typesetting <br />industry. Lorem Ipsum has been the
              <br />industry's standard dummy text ever since the 1500s,
            </div>
          </div>
          <div class="servic-block">
            <div class="servic-wrapper__image">
              <img src="@/assets/img/wall1.svg" alt="" />
            </div>
            <div class="servic-item__title">HEADING 10</div>
            <div class="servic-item__subtitle">
              Lorem Ipsum is simply dummy <br />text of the printing and
              typesetting <br />industry. Lorem Ipsum has been the
              <br />industry's standard dummy text ever since the 1500s,
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Servic",
};
</script>

<style lang="scss" scoped>
.servic {
  padding: 50px 0px;
  background: #4385f5;
}
.servic-info {
  color: white;
  display: flex;
  gap: 30px;
  justify-content: center;
  margin-bottom: 50px;
}
.servic-info__title {
  font-size: 40px;
  font-weight: bold;
}
.servic-info__subtitle {
  font-size: 13px;
}
.servic-block {
  display: flex;
  flex-direction: column;
  gap: 10px;
  color: white;
  padding: 10px 10px 50px 10px;
  border: 2px solid #282828;
}
.servic-item__title {
  font-size: 20px;
}
.servic-wrapper__item {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.servic-wrapper__image {
  width: 100%;
}
@media screen and (max-width: 992px) {
  .servic-wrapper__item {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
  }
}
@media screen and (max-width: 768px) {
  .servic-info__title {
    font-size: 30px;
  }
  .servic-info {
    gap: 10px;
    margin-bottom: 20px;
  }
}
@media screen and (max-width: 576px) {
  .servic-info {
    display: flex;
    flex-direction: column;
    text-align: center;
  }
  .servic-wrapper__item {
    display: flex;
    flex-direction: column;
  }
}
</style>
