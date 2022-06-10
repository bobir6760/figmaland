<template>
  <div class="best">
    <div class="container">
      <div class="best-wrapper">
        <div class="best-item__title">
          The best products <br />start with Figma
        </div>
        <div class="best-item__subtitle">
          Most calendars are designed<br />
          for teams. Slate is designed for freelancers
        </div>
        <button class="best-btn">Try For Free</button>
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
  display: flex;
  background-image: url("~@/assets/img/GARA.jpg");
  background-size: cover;
  text-align: center;
  min-height: 80vh;
  padding: 100px 0 50px 0;
  width: 100%;
}

.best-wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 80%;
}

.best-title {
  color: white;
}

.best-item__title {
  font-size: 80px;
  font-weight: bold;
  color: white;
  cursor: pointer;
}
.best-item__subtitle {
  font-size: 30px;
  margin-top: 50px;
  color: white;
  cursor: pointer;
}
.best-btn {
  cursor: pointer;
  padding: 16px 62px;
  background: #2442b2;
  color: white;
  border: none;
  margin-top: 60px;
  border-radius: 10px;
}
.best-btn:active {
  color: white;
  background-color: #6C8BF7;
  font-size: 18px;
}
@media screen and (max-width: 992px) {
  .best-item__title {
    font-size: 60px;
  }
  .best-item__subtitle {
    font-size: 25px;
  }
}

@media screen and (max-width: 768px) {
  .best-item__title {
    font-size: 50px;
  }
  .best-item__subtitle {
    font-size: 20px;
  }
}

@media screen and (max-width: 576px) {
  .best-item__title {
    font-size: 40px;
  }
  .best-item__subtitle {
    font-size: 15px;
  }
}
</style>
