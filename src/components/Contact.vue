<template>
  <div class="contact">
    <div class="container">
      <div class="contact-wrapper">
        <div class="contact-wrapper__item">
          <div class="contact-title">Contact Us</div>
          <div class="contact-subtitle">
            Most calendars are designed for teams.<br />Slate is designed for
            freelancers
          </div>
        </div>

        <div class="contact-body">
          <div class="contact-cards">
            <div class="contact-cards__title">Contact Us</div>
            <div class="contact-set">
              <input placeholder="Your Name" type="text" />
              <input placeholder="Your Email" type="text" />
              <textarea
                placeholder="Your Meesage"
                name=""
                id=""
                cols="30"
                rows="10"
              ></textarea>
            </div>
            <button class="contact-button">Send</button>
          </div>

          <div class="contact-wrapper__map">
            <div class="contact-wrapper__address">
              <div class="contact-address">
                <div class="contact-icon">
                  <img src="@/assets/img/Location2.svg" alt="" />
                </div>
                <div class="contact-address__title">
                  6386 Spring St undefined Anchorage, <br />Georgia 12473 United
                  States
                </div>
              </div>
              <div class="contact-address">
                <div class="contact-icon">
                  <img src="@/assets/img/Phone2.svg" alt="" />
                </div>
                <div class="contact-address__title">(843) 555-0130</div>
              </div>
              <div class="contact-address">
                <div class="contact-icon">
                  <img src="@/assets/img/Pochta2.svg" alt="" />
                </div>
                <div class="contact-address__title">
                  willie.jennings@example.com
                </div>
              </div>
            </div>

            <div class="contact-image">
              <img src="@/assets/img/MAP.png" alt="" />
            </div>
            <div class="contatc-set__icon">
              <img src="@/assets/img/Twitter2.svg" alt="" />
              <img src="@/assets/img/Facebook2.svg" alt="" />
              <img src="@/assets/img/IN2.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style lang="scss" scoped>
.contact {
  padding: 50px 0;
}
.contact-wrapper__item {
  text-align: center;
}
.contact-title {
  padding-bottom: 10px;
  font-size: 50px;
  cursor: pointer;
}
.contact-subtitle {
  padding-bottom: 50px;
  font-size: 30px;
  cursor: pointer;
}
.contact-body {
  display: flex;
  justify-content: space-around;
  padding: 50px 0px;
  gap: 50px;
}
.contact-cards {
  flex-direction: column;
  padding: 52px 50px;
  border: 1px solid #dddddd;
  box-sizing: border-box;
  border-radius: 20px;
  width: 35%;
}
.contact-cards__title {
  text-align: center;
  font-size: 20px;
  font-weight: bold;
  padding-bottom: 20px;
  cursor: pointer;
}
.contact-button {
  background: #2442B2;
  border-radius: 5px;
  border: none;
  color: white;
  margin-top: 30px;
  padding: 15px 130px;
  font-size: 20px;
  align-self: flex-start;
  cursor: pointer;
}
.contact-button:active {
  color: white;
  background-color: #6c8bf7;
}
.contact-button:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.9);
}
.contact-set input {
  border-radius: 5px;
  padding: 22px 50px 12px 15px;
  margin-bottom: 45px;
  background: #f5f5f5;
  border: none;
  width: 100%;
}
.contact-set textarea {
  width: 100%;
  background: #f5f5f5;
  border: 1px solid #e8e8e8;
  padding: 20px;
  outline: none;
}
.contact-wrapper__address {
  display: flex;
  padding: 50px 0px;
  justify-content: space-between;
  text-align: center;
  align-items: center;
  gap: 20px;
}
.contact-image img {
  padding-left: 40px;
  width: 100%;
  cursor: pointer;
}
.contatc-set__icon img {
  padding: 50px 20px 0px 0px;
  width: 70px;
  height: 100px;
  object-fit: contain;
  cursor: pointer;
}
.contact-icon img {
object-fit: contain;
width: 40px;
height: 40px;
cursor: pointer;
}
.contact-address__title {
  cursor: pointer;
}
@media screen and (max-width: 1200px) {
  .contact-button {
    padding: 20px 90px;
  }
}

@media screen and (max-width: 992px) {
  .contact-button {
    padding: 20px 100px;
  }
  .contact-cards {
    width: 50%;
  }
  .contact-title {
    font-size: 40px;
  }
  .contact-subtitle {
    font-size: 23px;
  }
}

@media screen and (max-width: 768px) {
  .contact-title {
    font-size: 30px;
  }
  .contact-subtitle {
    font-size: 20px;
    padding: 0px;
  }

  .contact-wrapper__address {
    flex-direction: column;
    padding: 10px;
  }
  .contact-button {
    padding: 17px 106px;
  }
  .contact-cards {
    width: 50%;
  }

  .contact-body {
    flex-direction: column;
    align-items: center;
  }

  .contact-image img {
    width: 100%;
    padding: 0px;
  }
  .contatc-set__icon img {
    text-align: center;
    padding: 0px;
    width: 50px;
    height: 50px;
    object-fit: contain;
  }
  .contatc-set__icon {
    text-align: center;
  }
}
@media screen and (max-width: 576px) {
  .contact-title {
    font-size: 25px;
  }
  .contact-subtitle {
    font-size: 15px;
    padding-bottom: 10px;
  }

  .contact-wrapper__address {
    flex-direction: column;
    padding-top: 0px;
  }

  .contact-button {
    padding: 15px 25px;
  }
  .contact-cards {
    width: 100%;
    padding: 30px;
  }

  .contact-body {
    flex-direction: column;
    padding-top: 10px;
  }
  .contact-image img {
    width: 100%;
    padding: 0px;
  }

  .contact-button {
    padding: 15px 97px;
    font-size: 15px;
  }
  .contatc-set__icon {
    text-align: center;
  }
}
</style>
