<template lang="pug">
  .cont_principal.mb-4(data-aos="fade-up")
    .row
      .col-auto.pe-2
        figure
          img(src="@/assets/curso/decorativo.svg")
      .col.ps-0(style="place-self:center;")
          h3.text-white.mb-0.titulo(v-text="titulo")
</template>
<script>
export default {
  props: {
    titulo: {
      type: String,
      default: '',
    },
  },
}
</script>
<style lang="sass">
.cont_principal
  max-width: fit-content
.cont_principal, .cont_principal *
  position: relative
.cont_principal:before
  content: ''
  position: absolute
  width: 86%
  height : 80%
  background-color: #30169a
  bottom: 10%
  top: 10%
  border-radius: 10% / 30px
  left: 49px
.cont_principal .titulo
  z-index: 2
  padding-right: 10px
</style>
