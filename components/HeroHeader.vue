<template>
  <div class="hero__Header">
   
    <h1><span>Hi</span>, it's me... Henri</h1>
  </div>
</template>

<style lang="scss" scoped>
.hero__Header {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  h1 span {
    color: #38e2b3;
  }
}
canvas {
  width: 100%;
  height: 100%;
  outline: none;
}
#container {
  width: 100%;
  height: 100%;
  position: relative;
}

.spline-watermark {
  position: absolute;
  bottom: 16px;
  right: 16px;
  width: 32px;
  height: 32px;
  z-index: 2;
}
.spline-watermark:hover {
  opacity: 0.8;
}
.spline-watermark img {
  display: block;
  width: 100%;
  height: 100%;
}
</style>
