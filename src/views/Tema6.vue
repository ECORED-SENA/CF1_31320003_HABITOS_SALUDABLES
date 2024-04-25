<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 La pirámide de la alimentación

    .col-xl-9.m-auto
      .p-3(style="background-color:#F1EBE0;border-radius:15px;" data-aos="zoom-in")
        .row
          .col-auto(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema6/1.svg")
          .col(style="place-self:center;")
            p.mb-0 La pirámide de la alimentación es una figura geométrica que orienta a las personas sobre la perspectiva de una dieta equilibrada diaria.
    
    p.mt-4(data-aos="fade-right") La pirámide de alimentos subraya algunos conceptos de suma importancia: 

    .cont_6_1.mt-4
      .row
        .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-8.col-md-7.col-lg-12
            img(src="@/assets/curso/tema6/3.png")
        .col-lg-7(data-aos="fade-left")
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
            .row.col-xl-11.m-auto(titulo="Variedad")
              p Uno de los inconvenientes más usuales en la alimentación es la monotonía, debido a que, por lo general, se come lo mismo; por eso la variedad es un factor importante en el equilibrio nutricional. 
              p Hay que tener claro que ningún alimento aporta todos los nutrientes en las cantidades necesarias, por eso la dieta diaria debe contener los principales grupos de alimentos (ningún grupo de nutrientes es más importante que otro). 
            .row.col-xl-11.m-auto(titulo="Proporcionalidad")
              p Se aconseja comer la mayor cantidad de alimentos que se encuentran en la base de la pirámide y en menor proporción los que se hallan en la parte superior. Los nutrientes que se consumen deben ser en las cantidades adecuadas y suficientes, evitando excesos. 
            .row.col-xl-11.m-auto(titulo="Moderación ")
              p Se recomiendan alimentos en porciones moderadas en número y tamaño, según las necesidades de energía de cada persona en particular. Seguir las pautas dadas ayuda a prevenir algunas enfermedades como la obesidad. 

      TituloDecorativo.mt-5(titulo="Niveles de la pirámide de alimentación")

      .row
        .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
          ul.lista-ul
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong Primer nivel:] está ubicado en la base de la pirámide y los alimentos que se encuentran allí son de tipo energético, es decir, aportan calorías al organismo, como por ejemplo cereales, arroz, pan, pasta y papas. Se recomienda que el consumo de este grupo vaya de cuatro a seis raciones al día. 
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong Segundo nivel:] en este nivel están las frutas y las verduras. Este grupo de alimentos aporta a la dieta fibra, vitaminas y antioxidantes, aspectos requeridos por todas las edades. Se aconsejan de dos a tres raciones diarias de estos alimentos.
        .col-lg-6(data-aos="fade-left")
          figure.m-auto.col-12.col-md-10.col-lg-12
            img(src="@/assets/curso/tema6/4.svg") 
      
      .row.mt-4
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-9.col-md-8.col-lg-12
            img(src="@/assets/curso/tema6/5.svg") 
        .col-lg-8(data-aos="fade-left")
          .p-4(style="background-color:#EBEBFD;border-radius:12px;")
            ul.lista-ul.mb-0
              li.d-flex.mb-0
                i.fas.fa-walking(style="color:#30169A;")
                div 
                  p #[strong Tercer nivel:] comprende lácteos, carnes, mariscos, huevos y frutos secos. Dentro de los derivados lácteos se hallan la leche, el queso y el yogur. 
                  p A las personas con sobrepeso se les recomienda consumir estos alimentos semidescremados, lo aconsejable son dos raciones al día. En el grupo de las carnes, se sugiere la alimentación con pescado, porque es el más aportante en hierro y grasas esenciales. De las carnes rojas las más favorables son las magras, ricas en proteínas, hierro y zinc; lo saludable son dos raciones al día. 
                  p.mb-0 Los frutos secos pertenecen a este nivel porque tienen un alto contenido proteico. Aquí también se hallan las legumbres, las cuales aportan proteínas de muy buena calidad nutricional; la ración recomendada para los frutos secos es de tres a siete porciones semanales, y para las legumbres, de tres raciones semanales. 
          ul.lista-ul.mt-4
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong Cúspide de la pirámide:] allí se encuentran productos que tienen una gran cantidad de grasas como las aceitunas y los aceites vegetales (girasol, oliva, maíz y soya). El consumo de estos productos debe ser moderado, porque aportan muchas calorías y además se almacenan con facilidad en el cuerpo. 






</template>

<script>
import TituloDecorativo from '../components/TituloDecorativo.vue'
export default {
  name: 'Tema6',
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
.cont_6_1, .cont_6_1 *
  position: relative
.cont_6_1:before
  content: ''
  position: absolute
  width: 125%
  height: 85%
  bottom: 15%
  left: -15%
  background: url(../assets/curso/tema6/2.png)
  background-size: 100% 100%
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
