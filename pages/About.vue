<template>
  <div class="container">
    <div class="header">
      <h2>About me</h2>
    </div>
    <div class="paragraph">
      <p>
        Hi, I'm Denis – UX/UI designer from Minsk.<br />
        I'm interested in design and everything connected with it.<br />
        <br />
        <br />
        I'm studying at courses "Web and mobile design <br />
        interfaces" in IT-Academy.<br />
        <br />
        <br />
        Ready to implement excellent projects <br />
        with wonderful people.
      </p>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.container {
  width: 65%;
  height: 507px;
  margin-top: 35px;
  margin-left: auto;
  margin-right: auto;
  background: #f6f6f6;
}

.header {
  padding-top: 50.25px;
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

@media (max-width: 737px) {
  .container {
    width: 80%;
  }

  .header {
    padding-top: 10px;
  }
}

@media (max-width: 515px) {
  .container {
    width: 88%;
    height: 478px;
    margin-top: 25px;
  }

  .header {
    font-size: 22px;
    line-height: 33px;
  }

  .paragraph {
    font-size: 15px;
    line-height: 25px;
  }
}
</style>
