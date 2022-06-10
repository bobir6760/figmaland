<template>
  <div class="features">
    <div class="container">
      <div class="features-wrapper">
        <div class="features-wrapper__title">Features</div>
        <div class="features-wrapper__subtitle">
          Most calendars are designed for teams.<br />Slate is designed for
          freelancers
        </div>
        <div class="features-block">
          <div class="features-item">
            <div class="features-wrapper-icon">
              <img src="@/assets/img/vector1.svg" alt="" />
            </div>
            <div class="features-title">
              OpenType features <br />Variable fonts
            </div>
            <div class="features-subtitle">
              Slate helps you see how many more days you need to work to reach
              your financial goal.
            </div>
          </div>
          <div class="features-item">
            <div class="features-wrapper-icon">
              <img src="@/assets/img/Vector2.svg" alt="" />
            </div>
            <div class="features-title">Design with real data</div>
            <div class="features-subtitle">
              Slate helps you see how many more days you need to work to reach
              your financial goal.
            </div>
          </div>
          <div class="features-item">
            <div class="features-wrapper-icon">
              <img src="@/assets/img/vector3.svg" alt="" />
            </div>
            <div class="features-title">Fastest way to take action</div>
            <div class="features-subtitle">
              Slate helps you see how many more days you need to work to reach
              your financial goal.
            </div>
          </div>
        </div>
        <div class="features-image">
          <img src="@/assets/img/Dizayner.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
};
</script>

<style lang="scss" scoped>
.features {
  padding: 50px 0px;
}
.features-wrapper {
  text-align: center;
}
.features-wrapper__title {
  font-size: 50px;
  font-weight: normal;
  margin-bottom: 20px;
  cursor: pointer;
}
.features-wrapper__subtitle {
  font-size: 30px;
  margin-bottom: 30px;
  cursor: pointer;
}
.features-title {
  font-size: 20px;
  font-weight: bold;
  padding-bottom: 20px;
  cursor: pointer;
}
.features-subtitle {
  font-size: 20px;
  cursor: pointer;
}
.features-block {
  display: flex;
  align-items: center;
  margin-bottom: 50px;
  gap: 50px;
}
.features-image img {
  width: 100%;
}
.features-wrapper-icon img {
  padding-bottom: 10px;
  width: 70px;
  height: 70px;
  object-fit: contain;
  cursor: pointer;
}
@media screen and (max-width: 992px) {
  .features-block {
    flex-direction: column;
    align-items: center;
  }
  .features-wrapper__subtitle {
    font-size: 35px;
  }
}


@media screen and (max-width: 768px) {
  .features-block {
    flex-direction: column;
    align-items: center;
  }
  .features-wrapper__subtitle {
    font-size: 30px;
  }
  .features-wrapper__title {
    font-size: 40px;
  }
}

@media screen and (max-width: 576px) {
  .features-block {
    flex-direction: column;
    align-items: center;
  }
  .features-wrapper__subtitle {
    font-size: 20px;
  }
  .features-wrapper__title {
    font-size: 35px;
  }
}
</style>
