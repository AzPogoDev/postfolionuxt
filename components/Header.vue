<template>
  <header>
    <div class="container">
      <div class="header">
        <nav class="nav">
          <a href="/" class="nav-logo"
            ><img
              src="https://d33wubrfki0l68.cloudfront.net/6e818a6053f5a11d48f2070de259173df357290c/207d7/_assets/_images/spline_logo.png"
              alt="Spline"
          /></a>
          <ul class="nav-menu">
            <li class="nav-menu-download">
              <a href="#download">Infos</a>
            </li>
            <li class="nav-menu-download">
              <a href="#download">Infos</a>
            </li>
            <li class="nav-menu-download">
              <a href="#download">Infos</a>
            </li>
            <li class="nav-menu-download">
              <a href="#download">Infos</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  position: fixed;
  z-index: 10;
  width: 100%;
  left: 0;
  right: 0;
}
.header .nav {
  margin-left: -8px;
  width: 490px;
  grid-gap: 16px;
  display: grid;
  grid-template-columns: auto 1fr;
  padding-top: 24px;
  background: rgba(29, 29, 29, 0.9);
  padding: 8px;
  border-radius: 100px;
  margin-top: 16px;
  align-items: center;
  backdrop-filter: blur(10px);
}
.nav-logo img {
  width: 48px;
}
ul.nav-menu {
  width: 100%;
  display: grid;
  grid-template-columns: auto auto auto auto;
  align-items: center;
  padding: none;
  grid-gap: 8px;
  padding: 0 8px 0 0;
  list-style: none;
  margin: 0;
}
li {
  font-size: 16px;
  color: #ffffff86;
  width: 100%;
  text-align: center;
}
</style>
