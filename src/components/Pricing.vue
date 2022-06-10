<template>
  <div class="pricing">
    <div class="container">
      <div class="pricing-wrapper">
        <div class="pricing-item">
          <div class="pricing__title">Pricing</div>
          <div class="pricing__subtitle">
            Most calendars are designed for teams. <br />Slate is designed for
            freelancers
          </div>
        </div>
        <div class="pricing-cards">
          <div class="pricing-free">
            <div class="pricing-content">
              <div class="pricing-content__title">FREE</div>
              <div class="pricing-content__subtitle">
                Organize across all <br />apps by hand
              </div>
            </div>
            <div class="pricing-element">
              <div class="pricing-element__number">0</div>
              <div class="pricing-text">
                <div class="pricing-text__title">$</div>
                <div class="pricing-text__subtitle">Per Month</div>
              </div>
            </div>
            <div class="pricing-body">
              <div class="pricing-body__title">Pricing Feature</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
            </div>
            <button class="pricing-button">Order</button>
          </div>
          <div class="pricing-free">
            <div class="pricing-content">
              <div class="pricing-content__title">FREE</div>
              <div class="pricing-content__subtitle">
                Organize across all <br />apps by hand
              </div>
            </div>
            <div class="pricing-element">
              <div class="pricing-element__number">10</div>
              <div class="pricing-text">
                <div class="pricing-text__title">$</div>
                <div class="pricing-text__subtitle">Per Month</div>
              </div>
            </div>
            <div class="pricing-body">
              <div class="pricing-body__title">Pricing Feature</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
            </div>
            <button class="pricing-button">Order</button>
          </div>
          <div class="pricing-free">
            <div class="pricing-content">
              <div class="pricing-content__title">FREE</div>
              <div class="pricing-content__subtitle">
                Organize across all <br />apps by hand
              </div>
            </div>
            <div class="pricing-element">
              <div class="pricing-element__number">99</div>
              <div class="pricing-text">
                <div class="pricing-text__title">$</div>
                <div class="pricing-text__subtitle">Per Month</div>
              </div>
            </div>
            <div class="pricing-body">
              <div class="pricing-body__title">Pricing Feature</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
              <div class="pricing-body__subtitle">Pricing</div>
            </div>
            <button class="pricing-button">Order</button>
          </div>
        </div>

        <div class="pricing-wrapper__block">
          <div class="pricing-block__title">Testimonials</div>
          <div class="pricing-wrapper__image">
            <img src="@/assets/img/IBM.png" alt="" />
          </div>
          <div class="pricing-wrapper__subtitle">
            Most calendars are designed for teams. Slate is designed for
            freelancers <br />who want a simple way to plan their schedule.
          </div>

          <div class="pricing-wrapper__logo">
            <div class="pricing-wrapper__icon">
              <img src="@/assets/img/Designer.svg" alt="" />
            </div>
            <div class="pricing-wrapper__text">
              <div class="pricing-logo__title">Organize across</div>
              <div class="pricing-logo__subtitle">Ui designer</div>
            </div>
          </div>
          <button class="pricing-text__btn">More Testimonials</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pricing",
};
</script>

<style lang="scss" scoped>
.pricing {
  padding: 50px 0px;
  background-color: #252b42;
}
.pricing-wrapper {
  text-align: center;
  padding-top: 100px;
}
.pricing__title {
  font-size: 50px;
  color: white;
  padding-bottom: 10px;
  cursor: pointer;
}
.pricing-content__subtitle {
  cursor: pointer;
}
.pricing-text__title {
  cursor: pointer;
}
.pricing-text__subtitle {
  cursor: pointer;
}
.pricing-body__title {
  cursor: pointer;
}
.pricing-body__subtitle {
  cursor: pointer;
}
.pricing__subtitle {
  font-size: 30px;
  color: white;
  padding-bottom: 80px;
  cursor: pointer;
}
.pricing-cards {
  display: flex;
  justify-content: center;
  padding-bottom: 50px;
  gap: 50px;
}
.pricing-free {
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: center;
  padding: 30px 15px;
  background: white;
  color: black;
  border-radius: 15px;
}
.pricing-element__number {
  font-size: 70px;
  font-weight: 900;
  padding-right: 10px;
  cursor: pointer;
}

.pricing-content__title {
  display: flex;
  justify-content: center;
  font-weight: 900;
  margin-bottom: 7px;
  cursor: pointer;
}
.pricing-text {
  display: flex;
  flex-direction: column;
  text-align: start;
}
.pricing-element {
  display: flex;
  align-items: center;
}
.pricing-body {
  display: flex;
  flex-direction: column;
  gap: 40px;
  align-items: center;
  padding-top: 30px;
}
.pricing-button {
  color: white;
  border-radius: 5px;
  background: #2442B2;
  padding: 15px 100px;
  margin-top: 30px;
  font-size: 18px;
  border: none;
  cursor: pointer;
}
.pricing-button:active {
  color: white;
  background-color: #6C8BF7;
  font-size: 18px;
}
.pricing-button:hover {
  box-shadow: 0 0 11px rgba(0, 0, 0, 0.9);
}
.pricing-wrapper__block {
  background: white;
  padding: 15px;
}
.pricing-block__title {
  font-size: 50px;
  color: black;
  padding: 50px 30px;
  cursor: pointer;
}
.pricing-wrapper__image img {
  width: 100px;
  height: 100px;
  object-fit: contain;
  cursor: pointer;
}
.pricing-wrapper__subtitle {
  font-size: 30px;
  padding-bottom: 60px;
  cursor: pointer;
}
.pricing-wrapper__logo {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: start;
  gap: 10px;
  padding-bottom: 50px;
  cursor: pointer;
}
.pricing-wrapper__icon img {
  width: 100%;
  cursor: pointer;
}
.pricing-text__btn {
  cursor: pointer;
  padding: 15px 60px;
  background: #2442B2;
  border-radius: 5px;
  color: white;
  border: none;
  margin-bottom: 50px;
}
.pricing-text__btn:active {
  color: white;
  background-color: #6c8bf7;
}
.pricing-text__btn:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.9);
}

@media screen and (max-width: 1200px) {
  .pricing-cards {
    gap: 25px;
  }
}

@media screen and (max-width: 992px) {
  .pricing-cards {
    flex-direction: column;
    align-items: center;
  }

  .pricing-free {
    max-width: 500px;
    width: 100%;
  }
  .pricing-block__title {
    font-size: 40px;
    padding: 20px;
  }
  .pricing-wrapper__subtitle {
    font-size: 20px;
    padding-bottom: 30px;
  }
  .pricing-wrapper__logo {
    padding-bottom: 30px;
  }
  .pricing-text__btn {
    margin-bottom: 20px;
  }
}
@media screen and (max-width: 768px) {
  .pricing-cards {
    flex-direction: column;
    align-items: center;
  }

  .pricing-free {
    max-width: 500px;
    width: 100%;
  }
  .pricing-block__title {
    font-size: 35px;
    padding: 10px;
  }
  .pricing-wrapper__subtitle {
    font-size: 15px;
    padding-bottom: 20px;
  }
  .pricing-wrapper__logo {
    padding-bottom: 25px;
  }
  .pricing-text__btn {
    margin-bottom: 15px;
  }
}
@media screen and (max-width: 576px) {
  .pricing-cards {
    flex-direction: column;
    align-items: center;
  }
  .pricing-free {
    max-width: 500px;
    width: 100%;
  }
  .pricing-block__title {
    font-size: 30px;
  }
  .pricing-wrapper__subtitle {
    font-size: 15px;
    padding-bottom: 20px;
  }
  .pricing-wrapper__logo {
    padding-bottom: 25px;
  }
  .pricing-text__btn {
    margin-bottom: 15px;
  }
}
</style>
