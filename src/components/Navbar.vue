<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar-wrapper">
        <div class="navbar-info">
          <div class="navbar-wrapper__title">LOGO</div>
          <div class="navbar-block">
            <div class="navbar-wrapper__subtitle">
              <span><p>HOME</p></span>
              <p>HOME 1</p>
            </div>
            <div class="navbar-wrapper__text">
              <div class="navbar-text">HOME 2</div>
              <button class="navbar-btn">Home Sub Field 1</button>
              <button class="navbar-btn">Home Sub Field 2</button>
            </div>
            <div class="navbar-wrapper__item">
              <div class="navbar-item__title">HOME 3</div>
              <div class="navbar-item__subtitle">CONTACT US</div>
            </div>
          </div>
        </div>
        <div class="navbar-wrapper__block">
          <div class="navbar-item">
            <div class="navbar-title">Lorem Ipsum is simply dummy</div>
            <div class="navbar-subtitle">Lorem Ipsum is simply dummy</div>
            <div class="navbar-block__body">
              <input
                placeholder="Insert Your Email*"
                type="text"
                name=""
                value=""
              />
              <button class="navbar-block__btn">Register</button>
            </div>
          </div>
          <div class="navbar-wrapper__image">
            <img src="@/assets/img/art1.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  padding: 50px 0px;
}
.navbar-info {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}
.navbar-block {
  display: flex;
  gap: 20px;
}
.navbar-wrapper__subtitle {
  display: flex;
  gap: 60px;
  span {
    color: #4385f5;
  }
}
.navbar-wrapper__item {
  display: flex;
  gap: 60px;
}
.navbar-wrapper__text {
  display: flex;
  flex-direction: column;
  text-align: center;
}
.navbar-text {
  padding-bottom: 10px;
}
.navbar-btn {
  padding: 10px 20px;
  color: white;
  background: black;
  cursor: pointer;
}
.navbar-btn:active {
  color: black;
  background: white;
}
.navbar-wrapper__title {
  font-size: 60px;
  padding: 20px 50px 25px 50px;
  background: #4385f5;
  color: white;
}
.navbar-wrapper__block {
  display: flex;
  align-items: center;
}
.navbar-title {
  font-size: 40px;
  text-transform: uppercase;
  font-weight: bold;
}
.navbar-wrapper__image img {
  width: 100%;
}
.navbar-subtitle {
  font-size: 25px;
  margin-bottom: 50px;
}
.navbar-block__btn {
  margin-left: 10px;
  padding: 10px 40px;
  background: #4385f5;
  color: white;
  border-radius: 2px;
  border: none;
  font-size: 15px;
  cursor: pointer;
}
.navbar-block__btn:active {
  color: black;
}
.navbar-wrapper__block input {
  padding: 10px 100px 10px 5px;
  font-size: 15px;
}
.navbar-block__body {
  display: flex;
}
@media screen and (max-width: 1200px) {
  .navbar-title {
    font-size: 30px;
    margin-bottom: 10px;
  }
  .navbar-subtitle {
    font-size: 25px;
    margin-bottom: 50px;
  }
}
@media screen and (max-width: 992px) {
  .navbar-wrapper__title {
    font-size: 40px;
  }
  .navbar-wrapper__subtitle {
    display: flex;
    gap: 10px;
  }
  .navbar-wrapper__item {
    gap: 10px;
  }
  .navbar-block {
    gap: 10px;
  }
  .navbar-title {
    font-size: 25px;
  }
  .navbar-subtitle {
    font-size: 15px;
    margin-bottom: 40px;
  }
  .navbar-wrapper__subtitle {
    font-size: 12px;
  }
  .navbar-text {
    font-size: 12px;
  }
  .navbar-btn {
    font-size: 12px;
  }
  .navbar-wrapper__item {
    font-size: 12px;
  }
  .navbar-info {
    margin-bottom: 50px;
  }
  .navbar-wrapper__block input {
    padding: 10px 40px 10px 5px;
    font-size: 12px;
  }
  .navbar-block__btn {
    font-size: 12px;
    padding: 10px 30px;
  }
}
@media screen and (max-width: 768px) {
  .navbar-btn {
    font-size: 10px;
    padding: 5px 15px;
  }
  .navbar-wrapper__title {
    font-size: 35px;
  }
  .navbar-wrapper__subtitle {
    font-size: 10px;
  }
  .navbar-wrapper__subtitle {
    font-size: 10px;
  }
  .navbar-text {
    font-size: 10px;
  }
  .navbar-wrapper__item {
    font-size: 10px;
  }
  .navbar-wrapper__block input {
    padding: 5px 30px 5px 2px;
    font-size: 10px;
  }
  .navbar-block__btn {
    font-size: 10px;
    padding: 5px 25px;
    margin-left: 5px;
  }
  .navbar-title {
    font-size: 20px;
  }
}
@media screen and (max-width: 576px) {
  .navbar-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }
  .navbar-wrapper__block {
    display: flex;
    flex-direction: column;
  }
  .navbar-title {
    font-size: 17px;
  }
  .navbar-btn {
    font-size: 10px;
    padding: 2px 8px;
  }
}
</style>
