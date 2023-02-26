<template>
  <div class="container">
    <div class="img-wraper">
      <img class="img" src="../public/Rectangle.png" alt="Rectangle" />
      <div class="text-wraper">
        <h4 class="header">People and Society</h4>

        <div class="paragraph">
          <p class="text-paragraph">
            Our guides to society deliver all<br />
            the social insight you need,<br />
            helping you understand how<br />
            people live, love and play today<br />
            and why communities are the<br />
            way they are.
          </p>

          <p class="text-footer">Shop Society Guides</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.container {
  width: 65%;
  height: 652px;
  margin-top: 40px;
  margin-right: auto;
  margin-left: auto;
  background: rgba(204, 204, 204, 0.3);
}

.img-wraper {
  padding-top: 76px;

  display: grid;
  grid-auto-flow: column;
  justify-items: center;
}
.img {
  width: 65%;
}

.text-wraper {
  width: 100%;
  padding-right: 20px;
}
.header {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 42px;
  color: #000000;
}

.text-paragraph {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 36px;
  line-height: 42px;
  font-size: 36px;
  line-height: 42px;
  color: #000000;
}
.text-footer {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 17px;
  line-height: 20px;
  text-decoration-line: underline;
  color: #000000;
}

@media (max-width: 1425px) {
  .img {
    width: 55%;
  }
  .text-wraper {
    margin-bottom: 40px;
  }
  .header {
    font-weight: 700;
    font-size: 31px;
    line-height: 38px;
  }

  .img-wraper {
    align-items: center;
  }

  .text-paragraph {
    font-size: 27px;
    line-height: 30px;
  }
}

@media (max-width: 1280px) {
  .img-wraper {
    padding-top: 26px;
  }
  .img {
    width: 75%;
  }
  .text-wraper {
    margin-top: 20px;
  }
  .header {
    font-size: 33px;
    line-height: 39px;
  }
  .text-paragraph {
    font-size: 21px;
    line-height: 24px;
  }
}

@media (max-width: 958px) {
  .img {
    width: 85%;
  }
  .header {
    font-size: 29px;
    line-height: 35px;
  }
}

@media (max-width: 844px) {
  .container {
    height: 772px;
  }
  .img-wraper {
    grid-auto-flow: row;
  }
  .img {
    width: 55%;
  }
  .text-wraper {
    text-align: center;
  }
}
@media (max-width: 737px) {
  .container {
    width: 80%;
  }
}

@media (max-width: 515px) {
  .container {
    width: 88%;
    height: 672px;
  }
}
</style>
