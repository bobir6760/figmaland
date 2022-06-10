<template>
  <div class="pages">
    <div class="container">
      <div class="pages-wrapper">
        <div class="pages-wrapper__item">
          <div class="pages-text">
            <div class="pages-text__title">Pages</div>
            <div class="pages-text__subtitle">Home</div>
            <div class="pages-text__subtitle">Product</div>
            <div class="pages-text__subtitle">Pricing</div>
            <div class="pages-text__subtitle">About</div>
            <div class="pages-text__subtitle">Contact</div>
          </div>
          <div class="pages-text">
            <div class="pages-text__title">Tomothy</div>
            <div class="pages-text__subtitle">Eleanor Edwards</div>
            <div class="pages-text__subtitle">Ted Robertson</div>
            <div class="pages-text__subtitle">Annette Russell</div>
            <div class="pages-text__subtitle">Jennie Mckinney</div>
            <div class="pages-text__subtitle">Gloria Richards</div>
          </div>
          <div class="pages-text">
            <div class="pages-text__title">Jane Black</div>
            <div class="pages-text__subtitle">Philip Jones</div>
            <div class="pages-text__subtitle">Product</div>
            <div class="pages-text__subtitle">Colleen Russell</div>
            <div class="pages-text__subtitle">Marvin Hawkins</div>
            <div class="pages-text__subtitle">Bruce Simmmons</div>
          </div>
        </div>

        <div class="pages-finish">
          <div class="pages-wrapper__finish">
            <div class="pages-location">
              <img src="@/assets/img/Location5.svg" alt="" />
            </div>
            <div class="pages-finish__title">
              7480 Mockingbird Hill undefined
            </div>
          </div>
          <div class="pages-wrapper__finish">
            <div class="pages-location">
              <img src="@/assets/img/Phone.svg" alt="" />
            </div>
            <div class="pages-finish__title">(239) 555-0108</div>
          </div>
          <div class="pages-location">
            <div class="pages-location__item">
              <img src="@/assets/img/Twitter.svg" alt="" />
              <img src="@/assets/img/Facebook.svg" alt="" />
              <img src="@/assets/img/IN.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pages",
};
</script>

<style lang="scss" scoped>
.pages {
  padding: 50px 0px;
  background-color: #252b42;
}
.pages-wrapper {
  display: flex;
  justify-content: space-around;
}
.pages-wrapper__item {
  display: flex;
  color: white;
  gap: 50px;
}
.pages-text {
  margin: 0px 20px;
}
.pages-text__title {
  font-weight: bold;
  font-size: 20px;
  padding-bottom: 20px;
  cursor: pointer;
}
.pages-text__subtitle {
  padding-bottom: 20px;
  cursor: pointer;
}
.pages-wrapper__finish {
  display: flex;
  align-items: center;
  text-align: center;
  color: white;
  gap: 15px;
}
.pages-location img {
  padding: 0px 5px 10px 0px;
  object-fit: contain;
  cursor: pointer;
}
.pages-location__item {
  display: flex;
  align-items: center;
  gap: 30px;
}
.pages-location__item img {
  width: 50px;
  height: 50px;
  object-fit: contain;
  cursor: pointer;
}
.pages-finish__title {
  cursor: pointer;
}
@media screen and(max-width: 992px) {
  .pages-wrapper {
    gap: 50px;
  }
  .pages-wrapper__finish {
    gap: 0px;
  }
}
@media screen and(max-width: 768px) {
  .pages-wrapper {
    flex-direction: column;
    text-align: center;
  }
  .pages-wrapper__finish {
    justify-content: center;
  }
  .pages-location__item {
    justify-content: center;
  }
  .pages-wrapper__item {
    justify-content: center;
  }
}
@media screen and (max-width: 576px) {
  .pages-wrapper__item {
    flex-direction: column;
    text-align: center;
    gap: 25px;
  }
  .pages-wrapper {
    gap: 20px;
  }
  .pages-location__item {
    gap: 10px;
  }
}
</style>
