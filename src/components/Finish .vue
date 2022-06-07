<template>
  <div class="finish">
    <div class="container">
      <div class="finish-wrapper">
        <div class="finish-info">
          <div class="finish-info__title">LET’S WORK TOGETHER</div>
          <div class="finish-wrapper__item">
            <div class="finish-title">
              <span><p>How Can We Help You?</p></span>
              <p>Name*</p>
              <p>Phone*</p>
              <p>Message</p>
            </div>
            <div class="finish-wrapper__title">
              <p>Email*</p>
              <p>Organization*</p>
            </div>
          </div>
          <div class="finish-wrapper__btn">
            <button class="finish-btn">Send</button>
          </div>
        </div>
        <div class="finish-block">
          <div class="finish-block__title">
            © Copyright 2022 | All Rights Reserved
          </div>
          <div class="finish-item">
            <div class="finish-item__title">Follow Us:</div>
            <div class="finish-item__image">
              <img src="@/assets/img/facebook.svg" alt="" />
            </div>
            <div class="finish-item__image">
              <img src="@/assets/img/instagram.svg" alt="" />
            </div>
            <div class="finish-item__image">
              <img src="@/assets/img/twitter.svg" alt="" />
            </div>
            <div class="finish-item__image">
              <img src="@/assets/img/in.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Finish",
};
</script>

<style lang="scss" scoped>
.finish {
  padding: 50px 0px;
  background: #f0eeee;
}
.finish-wrapper__item {
  display: flex;
  justify-content: space-around;
  color: #918f8f;
  align-items: center;
  font-size: 18px;
  margin-bottom: 50px;
}
.finish-info__title {
  text-align: center;
  color: #4385f5;
  font-size: 35px;
  font-weight: bold;
  margin-bottom: 40px;
}
.finish-title {
  display: flex;
  flex-direction: column;
  gap: 30px;
  span {
    color: #4385f5;
  }
}
.finish-wrapper__title {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.finish-btn {
  padding: 15px 35px;
  color: white;
  background: #4385f5;
  border: none;
  cursor: pointer;
}
.finish-btn:active {
  color: black;
}
.finish-wrapper__btn {
  display: flex;
  justify-content: center;
  margin-bottom: 50px;
}
.finish-block {
  background: #4385f5;
  color: white;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 30px;
}
.finish-item {
  display: flex;
  align-items: center;
}
.finish-item__title {
  font-size: 18px;
  padding-right: 20px;
}
.finish-item__image img {
  width: 100%;
  padding-left: 10px;
}
.finish-block__title {
  font-size: 18px;
}
@media screen and (max-width: 768px) {
  .finish-info__title {
    font-size: 30px;
  }
  .finish-title {
    font-size: 15px;
    gap: 15px;
  }
  .finish-wrapper__title {
    font-size: 15px;
  }
  .finish-btn {
    font-size: 12px;
  }
  .finish-block__title {
    font-size: 12px;
  }
  .finish-item__title {
    font-size: 12px;
    padding-right: 5px;
  }
}
@media screen and (max-width: 576px) {
  .finish-wrapper__item {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 20px;
  }
  .finish-block {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .finish-block__title {
    font-size: 14px;
  }
}
</style>
