<template>
  <div class="partners">
    <div class="container">
      <div class="partners-wrapper">
        <div class="partners-wrapper__item">
          <div class="partners__title">Partners</div>
          <div class="partners-subtitle">
            Most calendars are designed for teams. <br />Slate is designed for
            freelancers
          </div>
        </div>
        <div class="partners-block">
          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Google.png" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Amazon.png" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Microsoft.png" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Uber.png" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Dropbox.svg" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Google.png" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Uber.png" alt="" />
          </div>

          <div class="partners-images__item">
            <h5>Client Name</h5>
            <img src="@/assets/img/Amazon.png" alt="" />
          </div>
        </div>
        <button class="partners-btn">Try For Free</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Partners",
};
</script>

<style lang="scss" scoped>
.partners {
  padding: 50px 0px;
}
.partners-wrapper {
  text-align: center;
}
.partners__title {
  font-size: 50px;
  margin-bottom: 20px;
  cursor: pointer;
}
.partners-subtitle {
  font-size: 30px;
  margin-bottom: 80px;
  cursor: pointer;
}
.partners-btn {
  cursor: pointer;
  padding: 16px 62px;
  background: #2442b2;
  border-radius: 5px;
  color: white;
  border: none;
}
.partners-btn:active {
  color: white;
  background-color: #6c8bf7;
}
.partners-btn:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.9);
}
.partners-block {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding-bottom: 30px;
}
.partners-images__item {
  display: flex;
  flex-direction: column;
  padding: 30px 40px;
  color: #374754;
  border: 1px solid #d8d8d8;
}
.partners-images__item h5 {
  cursor: pointer;
}
.partners-images__item img {
  margin-top: 15px;
  width: 100%;
  cursor: pointer;
}
@media screen and (max-width: 992px) {
  .partners-block {
    display: flex;
    justify-content: center;
    margin-bottom: 30px;
  }
  .partners-images__item img {
    width: 70px;
  }
  .partners-subtitle {
    margin-bottom: 40px;
  }
}
@media screen and (max-width: 768px) {
  .partners-block {
    display: inline-block;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  .partners-images__item img {
    width: 70px;
  }
  .partners__title {
    font-size: 35px;
  }
  .partners-subtitle {
    font-size: 23px;
  }
}
@media screen and (max-width: 576px) {
  .partners-block {
    display: inline-block;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  .partners-images__item img {
    width: 70px;
  }
  .partners__title {
    font-size: 30px;
  }
  .partners-subtitle {
    font-size: 18px;
  }
}
</style>
