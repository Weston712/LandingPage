<template>
  <div class="container">
    <div class="header">Contacts</div>
    <div class="paragraph">
      <p class="text">
        Want to know more or just chat?<br />
        You are welcome!
      </p>
    </div>
    <div class="button-wraper">
      <button class="button">Send message</button>
      <div class="png-wraper">
        <div class="png-mess">
          <img src="../public/in.png" alt="in" />
        </div>
        <div class="png-mess">
          <img src="../public/instag.png" alt="instag" />
        </div>
        <div class="png-mess">
          <img src="../public/Be.png" alt="be" />
        </div>
        <div class="png-mess">
          <img src="../public/mess.png" alt="mess" />
        </div>
      </div>
    </div>
    <p class="text-footer">
      Like me on<br />
      LinkedIn, Instagram, Behance, Dribble
    </p>
  </div>
</template>

<script></script>

<style scoped>
.container {
  width: 50%;
  margin-left: auto;
  margin-right: auto;
}
.header {
  margin-top: 100px;
  font-family: "Gilroy-Bold";
  font-size: 34px;
  line-height: 42px;
  text-align: center;
  color: #070707;
}

.paragraph {
  margin-top: 20px;
  font-family: "Gilroy-Medium";
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #070707;
}

.button-wraper {
  text-align: center;
  margin-top: 29px;
}

.button {
  width: 203.48px;
  height: 42px;
  background: #070707;
  font-family: "Gilroy-Bold";
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #ffffff;
  cursor: pointer;
  border-radius: 12px 10px 5px;
}
.png-wraper {
  width: 70%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 85px;
  display: grid;
  grid-auto-flow: column;
  justify-content: space-evenly;
}

.png-mess {
  cursor: pointer;
}

.text-footer {
  margin-top: 45px;
  font-family: "Gilroy-Medium";
  font-size: 14px;
  line-height: 17px;
  text-align: center;
  color: #828282;
}

@media (max-width: 1013px) {
  .png-wraper {
    width: 100%;
  }
}

@media (max-width: 515px) {
  .container {
    width: 70%;
  }

  .header {
    margin-top: 50px;
  }

  .button {
    width: 251px;
    height: 42px;
    background: #000000;
    border-radius: 50px;
  }

  .png-wraper {
    width: 100%;
    justify-content: space-between;
  }
}
</style>
