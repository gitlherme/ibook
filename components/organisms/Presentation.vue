<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem saepe,
      recusandae obcaecati ratione molestiae sint, totam quaerat explicabo
      deserunt ea impedit illum modi, voluptatibus nisi eligendi perferendis
      eius in repellat. Lorem ipsum dolor sit amet consectetur adipisicing elit.
      Blanditiis nam eaque maxime eum eveniet quibusdam quam beatae libero
      reiciendis molestias! Doloremque suscipit iusto quo dolor impedit
      reiciendis porro doloribus qui. Lorem ipsum dolor sit amet consectetur,
      adipisicing elit. Magni enim est, debitis doloremque nostrum, dolorum
      eveniet veritatis officiis sint beatae sit ipsum, tempora rerum fugiat
      dolores et ex itaque odio! Lorem ipsum dolor sit, amet consectetur
      adipisicing elit. Magni deleniti reiciendis placeat ratione nostrum. Ut,
      fuga. Voluptatem necessitatibus consequatur fuga debitis temporibus
      consequuntur aut corporis excepturi officia, nihil eos at!
    </p>

    <img src="@/assets/img/presentation.svg" alt="Presentation" />
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
