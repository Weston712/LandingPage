<template>
  <div class="container">
    <div class="header">
      <h2>Skills</h2>
    </div>
    <div class="paragraph">
      <p>I work in such programs as</p>
    </div>
    <div class="skills">
      <div class="skills-ps">
        <img src="../public/ps.png" alt="PS" class="skills-img" />
        <div class="skills-paragraph">
          Adobe<br />
          Photoshop
        </div>
        <div class="skills-raiting">
          <img src="../public/raiting4.png" alt="raiting" class="skills-raiting-star" />
        </div>
      </div>
      <div class="skills-ai">
        <img src="../public/ai.png" alt="ai" class="skills-img" />
        <div class="skills-paragraph">
          Adobe<br />
          Illustrator
        </div>
        <div class="skills-raiting">
          <img src="../public/raiting3.png" alt="raiting" class="skills-raiting-star" />
        </div>
      </div>
      <div class="skills-ae">
        <img src="../public/ae.png" alt="ae" class="skills-img" />
        <div class="skills-paragraph">
          Adobe<br />
          After Effects
        </div>
        <div class="skills-raiting">
          <img src="../public/raiting4.png" alt="raiting" class="skills-raiting-star" />
        </div>
      </div>
      <div class="skills-figma">
        <img src="../public/figma.png" alt="figma" class="skills-img-figma" />
        <div class="skills-paragraph">Figma</div>
        <div class="skills-raiting-figma">
          <img src="../public/raiting4.png" alt="raiting" class="skills-raiting-star" />
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.container {
  width: 65%;
  margin-left: auto;
  margin-right: auto;
}

.header {
  font-family: "Gilroy-Bold";
  font-size: 34px;
  line-height: 42px;
  text-align: center;
  color: #070707;
}

.paragraph {
  font-family: "Gilroy-Medium";
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #070707;
}

.skills {
  margin-top: 82.82px;
  display: grid;
  grid-auto-flow: column;
  justify-content: space-around;
  margin-left: auto;
  margin-right: auto;
}

.skills-img {
  margin-left: 50px;
}
.skills-img-figma {
  margin-left: 64px;
}

.skills-paragraph {
  margin-top: 17px;
  font-family: "Gilroy-Bold";
  font-size: 14px;
  line-height: 17px;
  text-align: center;
  color: #828282;
}
.skills-raiting {
  margin-top: 37.4px;
}
.skills-raiting-figma {
  margin-top: 54px;
}

@media (max-width: 983px) {
  .skills-img {
    width: 32%;
    margin-left: 37px;
  }

  .skills-img-figma {
    width: 20%;
    margin-left: 46px;
  }

  .skills-raiting-star {
    width: 100px;
    margin-top: 1px;
    margin-left: 10px;
  }
}

@media (max-width: 515px) {
  .container {
    width: 88%;
  }

  .header {
    font-size: 22px;
    line-height: 33px;
  }

  .paragraph {
    font-size: 12px;
    line-height: 19px;
  }
  .skills {
    margin-top: 35px;
    grid-auto-flow: row;
  }

  .skills-img {
    width: 40%;
    margin-top: 40px;
    margin-left: 43px;
  }
  .skills-img-figma {
    width: 30%;
    margin-top: 40px;
    margin-left: 48px;
  }
  .skills-raiting {
    margin-top: 25.4px;
  }
  .skills-raiting-star {
    width: 100px;
    margin-top: 1px;
    margin-left: 20px;
  }
  .skills-raiting-figma {
    margin-top: 34px;
    padding-bottom: 40px;
  }
}
</style>
