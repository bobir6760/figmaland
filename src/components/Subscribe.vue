@
<template>
  <div class="subscribe">
    <div class="container">
      <div class="subscribe-wrapper">
        <div class="subscribe-images">
          <img src="@/assets/img/Pochta.png" alt="" />
        </div>
        <div class="subscribe-item">
          <div class="subscribe__title">At your fingertips</div>
          <div class="subscribe__subtitle">Lightning fast prototyping</div>
          <div class="subscribe-item__title">Subscribe to our Newsletter</div>
          <div class="subscribe-item__subtitle">
            Available exclusivery on Figmaland
          </div>
          <div class="subscribe-cards">
            <input placeholder="Your Email" type="text" />
            <button class="subscribe-cards__button">Subscribe</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Subscribe",
};
</script>

<style lang="scss" scoped>
.subscribe {
  display: flex;
  padding: 50px 0px;
}
.subscribe-wrapper {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 30px;
}
.subscribe__title {
  font-size: 20px;
  font-weight: 900;
  padding-bottom: 10px;
  cursor: pointer;
}
.subscribe__subtitle {
  font-size: 48px;
  padding-bottom: 15px;
  cursor: pointer;
}
.subscribe-item__title {
  font-weight: bold;
  font-size: 20px;
  cursor: pointer;
}
.subscribe-item__subtitle {
  font-size: 20px;
  color: #374754;
  cursor: pointer;
}
.subscribe-cards {
  display: flex;
  margin-top: 50px;
}
.subscribe-cards input {
  background: #e8e8e8;
  border-radius: 5px;
  border: none;
  padding: 10px 50px 10px 40px;
  margin-right: 20px;
  font-size: 15px;
  cursor: pointer;
}
.subscribe-cards__button {
  padding: 15px 50px;
  font-size: 15px;
  background: #2442B2;
  color: white;
  border-radius: 5px;
  border: none;
  cursor: pointer;
}
.subscribe-cards__button:active {
  color: white;
  background-color: #6c8bf7;
}
.subscribe-cards__button:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.9);
}
.subscribe-images img {
  width: 100%;
}
@media screen and (max-width: 992px) {
  .subscribe-wrapper {
    flex-direction: column;
  }
  .subscribe-cards {
    flex-direction: column;
    margin-top: 25px;
    gap: 20px;
  }
  .subscribe-cards input {
    margin-right: 0px;
  }
  .subscribe__subtitle {
    font-size: 40px;
  }
}

@media screen and (max-width: 768px) {
  .subscribe-wrapper {
    flex-direction: column;
  }
  .subscribe-cards {
    flex-direction: column;
    margin-top: 25px;
    gap: 20px;
  }
  .subscribe-cards input {
    margin-right: 0px;
  }
  .subscribe__subtitle {
    font-size: 30px;
  }
}
@media screen and (max-width: 576px) {
  .subscribe-wrapper {
    flex-direction: column;
  }
  .subscribe-cards {
    flex-direction: column;
    margin-top: 25px;
    gap: 20px;
  }
  .subscribe-cards input {
    margin-right: 0px;
  }
  .subscribe__subtitle {
    font-size: 25px;
  }
}
</style>
