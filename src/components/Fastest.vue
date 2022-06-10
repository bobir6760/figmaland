<template>
  <div class="fastest">
    <div class="container">
      <div class="fastest-wrapper">
        <div class="fastest-item">
          <div class="fastest-title">Fastest way to <br />organize</div>
          <div class="fastest-subtitle">
            Most calendars are designed for teams. <br />Slate is designed for
            freelancers
          </div>
          <button class="fastest-btn">Try For Free</button>
        </div>
        <div class="fastest-image">
          <img src="@/assets/img/Noutbook.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Fastest",
};
</script>

<style lang="scss" scoped>
.fastest {
  padding: 50px 0px;
}
.fastest-wrapper {
  display: flex;
  justify-content: space-between;
}
.fastest-title {
  font-size: 50px;
  margin-bottom: 20px;
  cursor: pointer;
}
.fastest-subtitle {
  font-size: 30px;
  margin-bottom: 30px;
  cursor: pointer;
}
.fastest-btn {
  cursor: pointer;
  padding: 16px 62px;
  background: #2442B2;
  border-radius: 5px;
  color: white;
  border: none;
}
.fastest-btn:active {
  color: white;
  background-color: #6C8BF7;
}
.fastest-btn:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.9);
}
.fastest-image img {
  width: 100%;
}
@media screen and (max-width: 992px) {
  .fastest-wrapper {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .fastest-wrapper {
    max-width: 720px;
    width: 100%;
  }
  .fastest-title {
    font-size: 35px;
  }
  .fastest-subtitle {
    font-size: 20px;
  }
}
@media screen and (max-width: 768px) {
  .fastest-wrapper {
    flex-direction: column;
    align-items: center;
    max-width: 700px;
    width: 100%;
  }
  .fastest-title {
    font-size: 35px;
  }
  .fastest-subtitle {
    font-size: 20px;
  }
}
@media screen and (max-width: 576px) {
  .fastest-wrapper {
    flex-direction: column;
    align-items: center;
    max-width: 700px;
    width: 100%;
  }
  .fastest-title {
    font-size: 30px;
  }
  .fastest-subtitle {
    font-size: 15px;
  }
  .fastest-image img {
    margin-top: 15px;
  }
}
</style>
