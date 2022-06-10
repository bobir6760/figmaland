<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar-wrapper">
        <div class="navbar-info">
          <div class="navbar-wrapper_item">
            <ul class="navbar-links">
              <p>Home</p>
              <p>Product</p>
              <p>Pricing</p>
              <p>About</p>
              <p>Contact</p>
            </ul>
            <div class="navbar-image">
              <img
                class="navbar-img"
                src="@/assets/img/Rectangle2.png"
                alt="logo"
              />
            </div>
          </div>

          <div class="navbar-socials">
            <div class="navbar-socials__item">
              <img src="@/assets/img/Twitter.svg" alt="" />
            </div>
            <div class="navbar-socials__item">
              <img src="@/assets/img/Facebook.svg" alt="" />
            </div>
            <div class="navbar-socials__item">
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
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  background: transparent;
  z-index: 100;
  padding: 30px 0px 30px 0px;
}
.navbar-wrapper_item {
  display: flex;
  align-items: center;
  gap: 50px;
}
.navbar-links {
  display: flex;
  color: white;
  gap: 30px;
  cursor: pointer;
}
.navbar-info {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.navbar-socials {
  display: flex;
  align-items: center;
  gap: 15px;
}
.navbar-socials img {
  width: 100%;
  cursor: pointer;
}
.navbar-image img {
  width: 100%;
  cursor: pointer;
}

@media screen and (max-width: 992px) {
  .navbar-links {
    display: none;
  }
  .navbar-socials img {
    width: 24px;
    height: 24px;
    object-fit: contain;
  }
}
</style>
