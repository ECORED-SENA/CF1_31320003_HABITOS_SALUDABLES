<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row
      .col-lg-9.mb-4.mb-lg-0(data-aos="zoom-in" style="place-self:center;")
        .row
          .col-lg-5.mb-4.mb-lg-0.pe-lg-0
            figure.m-auto.col-9.col-md-8.col-lg-12
              img(src="@/assets/curso/intro1.png")
          .col-lg-7.mb-4.mb-lg-0.ps-lg-0
            .h-100.p-4(style="background-color:#EBEBFD;")
              figure
                img(src="@/assets/curso/intro2.svg" style="max-width:100px;")
              p.mt-3.mb-0 El presente componente formativo, explica los diferentes compuestos presentes en los alimentos, como son los hidratos de carbono, las proteínas, los lípidos, las vitaminas y los minerales, su función en el desarrollo del ser humano, así como los diferentes grupos de alimentos y nutrientes presentes en cada uno de ellos. 
          p.mt-4 Luego, se estudiarán los conceptos y características de una alimentación saludable, haciendo énfasis sobre la reconocida pirámide de alimentos y se explica el valor energético de los nutrientes, así como su gasto energético total en reposo. 
          p.fw-bold(style="color:#30169A;" data-aos="fade-up" data-aos-delay="600" data-aos-easing="ease-in-sine") Bienvenido a este proceso de aprendizaje. 
      .col-lg-3(data-aos="fade-up" data-aos-delay="800" data-aos-offset="300" data-aos-easing="ease-in-sine")
        figure.m-auto.col-6.col-md-6.col-lg-12
          img(src="@/assets/curso/intro3.png")
    
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass"></style>
