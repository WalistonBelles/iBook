<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis vitae ea voluptatum maiores ex qui, eligendi atque molestias tenetur itaque perspiciatis quos exercitationem, obcaecati dolorem, quasi sit repudiandae iure nemo.
    </p>

    <img src="@/assets/img/presentation.svg" alt="Apresentação do iBook">
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
