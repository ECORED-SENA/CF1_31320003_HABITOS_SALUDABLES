<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Alimentación, nutrición y clasificación de los alimentos 

    p(data-aos="fade-up") Para comenzar con el estudio de la alimentación y nutrición, es importante que tengamos claros los siguientes conceptos:

    .cont_1_1.mt-4
      .row
        .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-7.col-md-7.col-lg-12
            img(src="@/assets/curso/tema1/1.png")
        .col-lg-9(data-aos="fade-left")
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
            .row.col-xl-11.m-auto(titulo="Alimentos")
              p.mb-0 Son productos naturales o que han sufrido algún tipo de trasformación mediante un proceso de elaboración, haciéndolos aptos para el consumo humano. Los alimentos son indispensables para la vida, porque aportan los nutrientes y la energía necesaria para que una persona conserve una buena salud, la cual le permita realizar todas sus actividades cotidianas. 
            .row.col-xl-11.m-auto(titulo="Nutrientes")
              p.mb-0 Son sustancias presentes en los alimentos como por ejemplo proteínas, vitaminas, carbohidratos, lípidos y minerales, las cuales cumplen diversas funciones en el organismo de un ser humano. Se debe tener en cuenta que deben suministrarse en las cantidades necesarias. 
            .row.col-xl-11.m-auto(titulo="Alimentación")
              p.mb-0 Es el proceso mediante el cual los seres vivos obtienen del entorno una serie de alimentos, con el fin de satisfacer las necesidades de nutrientes requeridas para su buen funcionamiento. En el caso del hombre, la selección de los alimentos es voluntaria y se da mediante diferentes factores socioeconómicos (disponibilidad de productos), culturales y psicológicos (preferencias). 
            .row.col-xl-11.m-auto(titulo="Nutrición")
              p.mb-0 Es la ciencia que estudia la relación entre los nutrientes y el organismo humano a nivel individual y colectivo a lo largo de la vida y por medio de diferentes situaciones fisiológicas y patológicas. Una buena nutrición en la población se genera a través del esfuerzo de múltiples disciplinas. 

      p.mt-4(data-aos="fade-right") Para que los alimentos conserven las sustancias nutritivas y obtener una buena nutrición, se requiere: 

      .row.mt-4
        .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
          .p-4.h-100(style="background-color:#787CF0;border-radius:15px;")
            .bg-white.mb-3.p-3(style="border-radius:15px;box-shadow:0px 0px 10px rgba(0,0,0,.25);")
              .row
                .col-auto(style="place-self:center;")
                  figure
                    img(src="@/assets/curso/tema1/2.svg")
                .col(style="place-self:center;")
                  p.mb-0 Implementar en el sector agropecuario nuevas tecnologías, las cuales garanticen alimentos en cantidades suficientes, sanos y con alto valor nutritivo. 
            .bg-white.mb-3.p-3(style="border-radius:15px;box-shadow:0px 0px 10px rgba(0,0,0,.25);")
              .row
                .col-auto(style="place-self:center;")
                  figure
                    img(src="@/assets/curso/tema1/3.svg")
                .col(style="place-self:center;")
                  p.mb-0 Que en la trasformación de materias primas en productos se empleen procedimientos que garanticen la conservación del valor nutritivo de los alimentos. 
            .bg-white.mb-3.p-3(style="border-radius:15px;box-shadow:0px 0px 10px rgba(0,0,0,.25);")
              .row
                .col-auto(style="place-self:center;")
                  figure
                    img(src="@/assets/curso/tema1/4.svg")
                .col(style="place-self:center;")
                  p.mb-0 Asegurar mediante leyes gubernamentales, que los alimentos si cumplen con las características nutritivas. 
            .bg-white.mb-3.p-3(style="border-radius:15px;box-shadow:0px 0px 10px rgba(0,0,0,.25);")
              .row
                .col-auto(style="place-self:center;")
                  figure
                    img(src="@/assets/curso/tema1/5.svg")
                .col(style="place-self:center;")
                  p.mb-0 Ratificar en el almacenamiento y transporte de los productos elaborados, que el alimento no va a perder sus propiedades nutritivas. 
            .bg-white.mb-3.p-3(style="border-radius:15px;box-shadow:0px 0px 10px rgba(0,0,0,.25);")
              .row
                .col-auto(style="place-self:center;")
                  figure
                    img(src="@/assets/curso/tema1/6.svg")
                .col(style="place-self:center;")
                  p.mb-0 Desarrollar programas educativos en las escuelas sobre nutrición y sobre su importancia en el desarrollo humano. 
            .bg-white.mb-3.p-3(style="border-radius:15px;box-shadow:0px 0px 10px rgba(0,0,0,.25);")
              .row
                .col-auto(style="place-self:center;")
                  figure
                    img(src="@/assets/curso/tema1/7.svg")
                .col(style="place-self:center;")
                  p.mb-0 Que los alimentos se ingieran de manera eficiente en todos los sectores de la población, haciendo énfasis en hogares infantiles y colegios. 
        .col-lg-4(data-aos="fade-left")
          figure.m-auto.col-7.col-md-7.col-lg-12
            img(src="@/assets/curso/tema1/8.png")
    
      p.mt-4(data-aos="fade-right") Los alimentos pueden clasificarse según: 

      .row.mt-4
        .col-lg-3.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_1_2.text-center(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4
              img(src="@/assets/curso/tema1/10.svg" style="max-width:100px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Su procedencia
            ul.lista-ul.mt-3
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Animal.
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Vegetal.
        .col-lg-3.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_1_2.text-center(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4
              img(src="@/assets/curso/tema1/11.svg" style="max-width:100px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Función de sus nutrientes: 
            ul.lista-ul.mt-3
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Proteínas.
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Carbohidratos.
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Grasas.
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Vitaminas.
        .col-lg-3.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_1_2.text-center(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4
              img(src="@/assets/curso/tema1/12.svg" style="max-width:100px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Papel en el organismo
            ul.lista-ul.mt-3
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Energético.
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Constructor.
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Regulador.
        .col-lg-3.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_1_2.text-center(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4
              img(src="@/assets/curso/tema1/13.svg" style="max-width:100px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Su composición nutricional
            ul.lista-ul.mt-3
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Grupos básicos. 
              li 
                i.fas.fa-walking(style="color:#787CF0;")
                | Grupo de alimentos complementarios.


      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
.cont_1_1, .cont_1_1 *
  position: relative
.cont_1_1:before
  content: ''
  position: absolute
  width: 125%
  height: 90%
  left: -15%
  top: 10%
  background: rgb(239,250,244)
  background: linear-gradient(180deg, rgba(239,250,244,0) 0%, rgba(239,250,244,0.633578431372549) 15%, rgba(239,250,244,1) 40%, rgba(239,250,244,1) 50%, rgba(239,250,244,0.583158263305322) 80%, rgba(239,250,244,0) 100%)
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
.cont_1_2
  background: url(../assets/curso/tema1/9.png)
  background-size: 100% 100%
</style>
