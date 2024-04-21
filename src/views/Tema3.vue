<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Nutrientes presentes en los principales grupos de alimentos 
    
    .col-xl-10.m-auto
      .p-3(style="background-color:#F1EBE0;border-radius:15px;" data-aos="zoom-in")
        .row
          .col-auto(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema3/1.svg")
          .col(style="place-self:center;")
            p.mb-0 A continuación, se mencionan los principales nutrientes en los alimentos. 
    
    
    TituloDecorativo.mt-5(titulo="La leche y sus derivados")

    p(data-aos="fade-right") Son alimentos que contienen proteínas, grasas y carbohidratos. 
    
    .row.mt-4
      .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-7.col-md-7.col-lg-12
          img(src="@/assets/curso/tema3/2.png")
      .col-lg-9(data-aos="fade-left")
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Leche")
            .col-lg-7.mb-4.mb-lg-0
              ul.lista-ul.mb-0
                li.d-flex 
                  i.fas.fa-walking(style="color:#30169A;")
                  div Las proteínas de la leche como la caseína y la lactoalbúmina, tienen alto valor biológico. 
                li.d-flex 
                  i.fas.fa-walking(style="color:#30169A;")
                  div El carbohidrato de la leche es la lactosa, un disacárido compuesto por glucosa y galactosa. 
                li.d-flex 
                  i.fas.fa-walking(style="color:#30169A;")
                  div La leche contiene vitaminas liposolubles como la A, D, B12, calcio y fósforo. 
                li.d-flex 
                  i.fas.fa-walking(style="color:#30169A;")
                  div La grasa presente en la leche se conforma de ácidos grasos saturados. 
                li.d-flex 
                  i.fas.fa-walking(style="color:#30169A;")
                  div En el mercado hay tres tipos de leche, entera con 3,5 % de grasa, semidescremada con 1,5 % de grasa y desnatada con 0,5 % de grasa. 
            .col-lg-5
              figure.m-auto.col-9.col-md-8.col-lg-12
                img(src="@/assets/curso/tema3/3.png")
          .row.col-xl-11.m-auto(titulo="Queso")
            .col-lg-7.mb-4.mb-lg-0
              p Este alimento tiene proteínas de alto valor biológico, calcio, y vitaminas A, B2, B12, D, E, K; además abarca un alto nivel graso, haciéndolo un producto rico en calorías, por lo que se aconseja consumir quesos desnatados. 
              p.mb-0 Hay que tener en cuenta que los quesos curados son ricos en grasas, pero estos pierden los carbohidratos en el proceso de elaboración. 
            .col-lg-5
              figure.m-auto.col-9.col-md-8.col-lg-12
                img(src="@/assets/curso/tema3/4.png")
          .row.col-xl-11.m-auto(titulo="Yogur")
            .col-lg-7.mb-4.mb-lg-0
              p.mb-0 Este producto es un derivado de la leche, obtenido del proceso de adicionar un cultivo de microorganismos, los cuales se encargan de fermentar y de generar ácido láctico. El valor nutricional del yogur es similar al de la leche, pero tiene más disponibilidad de calcio por el pH ácido generado a partir de la fermentación. 
            .col-lg-5
              figure.m-auto.col-9.col-md-8.col-lg-12
                img(src="@/assets/curso/tema3/5.png")
    
    TituloDecorativo.mt-5(titulo="Proteínas")

    p(data-aos="fade-right") Son alimentos que contienen proteínas, grasas y carbohidratos. 





</template>

<script>
import TituloDecorativo from '../components/TituloDecorativo.vue'
export default {
  name: 'Tema3',
  components: {
    TituloDecorativo,
  },
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>
<style lang="sass">
.acordion__accion__btn--a
  background-color: #FCA651
  box-shadow: 0px 0px 7px 2px rgba(0,0,0,.3)
.acordion .tarjeta--azul
  background-color: #30169A
.acordion .tarjeta--azul h3
  color: #fff
.acordion .tarjeta.tarjeta--azul.acordion__activo
  background-color: #EBEBFD
.acordion .tarjeta.tarjeta--azul.acordion__activo h3
  color: #12263F
</style>
