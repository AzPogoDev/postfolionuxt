<template>
  <div class="index">
    <HeroHeader></HeroHeader>
    <div class="container">
      <div class="index__contentDescription">
        <h2>A french developer,<span> from Lille</span></h2>
        <p>
         Je suis un jeune développeur web de 21 ans, passionnée par les nouvelles technologiques et les expériences utilisateurs nouvelles !
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.index {
  &__contentDescription {
    text-align: center;
    p {
      font-size: 20px;
      max-width: 670px;
      margin: 1rem auto 3rem;
      color: grey;
      line-height: 1.5;
      font-weight: 500;
    }
  }
}
</style>
