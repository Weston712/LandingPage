<template>
  <div class="container">
    <div class="header">
      <div class="header-name">
        Denis <br />
        Novik
      </div>
      <div class="header-designer">
        UX | UI designer <br />
        24 years old, Minsk
      </div>
      <div class="header-eng">RU | ENG</div>
    </div>
    <div class="png">
      <img class="png-foto" src="../public/Group.png" alt="Group" />
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
  display: grid;
  grid-auto-flow: column;
  justify-content: space-between;
}

.header-name {
  font-family: "Gilroy-Bold";
  font-size: 47.3392px;
  line-height: 59px;
  color: #070707;
  margin-top: 39.69px;
}

.header-designer {
  font-family: "Gilroy-Medium";
  font-size: 18px;
  line-height: 22px;
  color: #070707;

  margin-top: 94.77px;
}

.header-eng {
  font-family: "Gilroy-Bold";
  font-size: 16px;
  line-height: 20px;
  color: #828282;
  transform: rotate(-90deg);
  margin-top: 55.5px;
  display: grid;
  align-items: end;
}

.png-foto {
  width: 102%;
  margin-top: 49.67px;
}

@media (max-width: 737px) {
  .container {
    width: 80%;
  }
}

@media (max-width: 515px) {
  .container {
    width: 88%;
  }

  .header-name {
    font-size: 37.3392px;
    line-height: 48px;
    margin-top: 40.69px;
  }

  .header-designer {
    font-size: 15px;
    line-height: 18px;
    margin-top: 84.77px;
  }

  .header-eng {
    font-size: 15px;
    line-height: 18px;
    margin-top: 45.5px;
  }

  .png-foto {
    margin-top: 50px;
  }
}
</style>
