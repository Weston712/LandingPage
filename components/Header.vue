<template>
  <div class="header">
    <div class="header-nav">
      <NuxtLink to="/" class="home-nav">Home</NuxtLink>
      <NuxtLink to="/about" class="about-nav">About me</NuxtLink>
      <NuxtLink to="/skills" class="skills-nav">Skills</NuxtLink>
      <NuxtLink to="/portfolio" class="portfolio-nav">Portfolio</NuxtLink>
      <NuxtLink to="/contacts" class="contacts-nav">Contacts</NuxtLink>
    </div>
    <div class="border"></div>
  </div>
</template>

<script></script>

<style scoped>
.header {
  width: 65%;
  margin-top: 26px;
  margin-left: auto;
  margin-right: auto;
}
.home-nav {
  font-family: "Gilroy-Bold";
  font-size: 18px;
  line-height: 22px;
  color: #070707;
  text-decoration: none;
}

.about-nav {
  text-decoration: none;
  color: #828282;
}

.skills-nav {
  text-decoration: none;
  color: #828282;
}

.portfolio-nav {
  text-decoration: none;
  color: #828282;
}

.contacts-nav {
  text-decoration: none;
  color: #828282;
}
.header-nav {
  font-family: "Gilroy-Bold";
  font-size: 18px;
  line-height: 22px;
  display: grid;
  grid-auto-flow: column;
  grid-template: repeat(165px, 1fr);
  justify-content: space-between;
  margin-left: auto;
  margin-right: auto;
}

.border {
  width: 100%;
  margin-top: 31.92px;
  margin-left: auto;
  margin-right: auto;
  border: 1px solid #828282;
  transform: matrix(1, 0, 0, 1, 0, 0);
}

@media (max-width: 737px) {
  .header {
    width: 80%;
  }
}

@media (max-width: 515px) {
  .header {
    width: 88%;
  }

  .home-nav {
    font-size: 12px;
    line-height: 19px;
  }
  .header-nav {
    font-size: 12px;
    line-height: 19px;
  }
  .border {
    margin-top: 20.92px;
  }
}
</style>
