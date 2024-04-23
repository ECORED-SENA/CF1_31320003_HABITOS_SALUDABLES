<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Alimentación saludable

    .row
      .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
        p La alimentación es fundamental, porque ayuda a que las personas alcancen un buen estado de salud. La alimentación junto con las bebidas que se ingieren, cubre las necesidades del organismo dependiendo de la dieta. 
        .row
          .col-lg-5.mb-4.mb-lg-0.pe-lg-0
            figure.col-10.m-auto.col-md-9.col-lg-12
              img(src="@/assets/curso/tema4/1.svg")
          .col-lg-7.ps-lg-0
            .p-4.p-lg-5.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#EFFAF4;")
              p Es importante tener en cuenta que el lugar donde se realizan los alimentos, como la forma en que se disfruta de estos, es casi tan significativo como lo que realmente se come. 
              p.mb-0 Cuando se habla de hábitos alimentarios, se hace referencia a la constancia adquirida durante las primeras etapas de la vida, los cuales siendo adecuados o no, perduran a veces durante toda la existencia de una persona. 
        p.mt-4 Los hábitos alimentarios están sujetos a la dieta que se  consume y a factores culturales, psicológicos, religiosos  y económicos, hallándose por ende una gran variedad  de dietas, las cuales varían dependiendo de aspectos  como el sexo, la edad, el país de origen y el estado fisiológico. 
      .col-lg-3(data-aos="fade-left" data-aos-delay="800")
        figure.m-auto.col-8.col-md-7.col-lg-12
          img(src="@/assets/curso/tema4/2.png")
    
    .row.mt-5
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-8.col-md-7.col-lg-12
          img(src="@/assets/curso/tema4/3.png")
      .col-lg-7(data-aos="fade-left")
        .row
          .col-auto
            figure
              img(src="@/assets/curso/tema4/4.svg")
          .col(style="place-self:center;")
            p.mb-0 Por lo tanto, es relevante conocer diferentes maneras  para seleccionar y combinar los alimentos, con el fin de  lograr una alimentación adecuada. 
        .p-3.mt-4(style="background-color:#EBEBFD;border-radius:5px;")
          p.mb-0 Una dieta o alimentación saludable es la mejor manera de contribuir a la realización de actividades diarias como el trabajo, el ejercicio, entre otras. 
        p.mt-4 Las características de una alimentación saludable son: 
        ul.lista-ul.mb-0.mt-3.ps-4
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div Aportar nutrientes y energía. 
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div Mantener los hábitos alimentarios de cada persona incluyendo gustos y costumbres. 
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div Ser sensorialmente agradable. 
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div Prevenir enfermedades no contagiosas como obesidad, hipertensión, diabetes y enfermedades cardiovasculares. 
    
    p.mt-4(data-aos="fade-right") Para que los ítems mencionados anteriormente se cumplan, se debe tener en cuenta lo siguiente: 

    TituloDecorativo.mt-5(titulo="Variación en la dieta")

    .cont_4_1
      .row
        .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
          .p-4.p-xl-5.h-100(style="background-color:#D0D1FA;border-radius:15px;")
            p.mb-0 Abarca todos los grupos de alimentos en las cantidades apropiadas, con el fin de tener una compensación de nutrientes entre grupos cuando exista déficit, de ahí la importancia del conocimiento sobre la combinación de alimentos. En la alimentación no se debe excluir ningún alimento, porque no hay nutrientes buenos ni malos; muchas veces el problema es la frecuencia con que se consumen las raciones diarias.
        .col-lg-6(data-aos="fade-left")
          figure.m-auto.col-12.col-md-10.col-lg-12
            img(src="@/assets/curso/tema4/6.svg")

      TituloDecorativo.mt-5(titulo="Equilibrio en la dieta")

      p(data-aos="fade-right") Permite una proporción entre la ingesta de calorías y el consumo energético, con el fin de mantener un peso corporal promedio, esto se puede dar mediante el suministro energético adecuado de cada uno de los macronutrientes, tales como lípidos, carbohidratos y proteínas, como se presenta a continuación. 

      .col-xl-9.m-auto.mt-4
        .row
          .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
            .p-4.h-100(style="background-color:#F6F6F6;border-radius:15px;")
              .titulo-sexto.color-acento-contenido
                h5 Figura 2
                span Gráfico de perfil calórico 
              figure
                img(src="@/assets/curso/tema4/7.svg" alt="La imagen presenta un perfil calórico, compuesto por proteínas, carbohidratos y lípidos.")
          .col-lg-4(data-aos="fade-left")
            .p-4.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#95DBB3;border-radius:15px;")
              figure
                img(src="@/assets/curso/tema4/8.svg" style="max-width:90px;display:inline;")
              p.mt-3.mb-0 Como se muestra en el gráfico, la ingesta recomendada de proteínas es de 10 %, de carbohidratos 60 %, y de lípidos 30 %. 

    p.mt-5(data-aos="fade-up") Una dieta equilibrada debe cumplir cinco aspectos básicos: 

    .row.mt-4
      .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Calorías suficientes")
            p.mb-0 Son necesarias para que el organismo realice de forma eficiente los procesos metabólicos y trabajos físicos.
          .row.col-xl-11.m-auto(titulo="Nutrientes proporcionados")
            p.mb-0 Proteínas, vitaminas y minerales, para que se desarrollen las funciones plásticas y reguladoras. 
          .row.col-xl-11.m-auto(titulo="Agua")
            p.mb-0 Es indispensable incluir en la dieta mínimo dos litros de agua al día; este elemento, aunque no es un nutriente, desempeña en el organismo procesos de asimilación y eliminación del sistema celular. 
          .row.col-xl-11.m-auto(titulo="Fibra dietaria")
            p.mb-0 Debe suministrarse en cantidades suficientes, porque aporta ligninas, polisacáridos y oligosacáridos. 
          .row.col-xl-11.m-auto(titulo="Equilibrio de nutrientes")
            p.mb-0 Todos los aportes calóricos deben estar equilibrados entre sí, según lo establecido por los expertos de la Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO) y la Organización Mundial de la Salud (OMS). 
      .col-lg-3(data-aos="fade-left" data-aos-delay="700")
        figure.m-auto.col-7.col-md-7.col-lg-12
          img(src="@/assets/curso/tema4/9.svg")
    
    .col-xl-10.m-auto.mt-4(data-aos="zoom-in")
      .cont_4_2.p-3(style="background-color:#77AF8F;border-radius:14px;")
        .row
          .col-auto.d-none.d-md-block
            figure
              img(src="@/assets/curso/tema4/11.svg")
          .col(style="place-self:center;")
            p.mb-0 Una alimentación saludable debe estar acompañada de buenos hábitos como por ejemplo la actividad física, y de una correcta hidratación, lo anterior para que el organismo se mantenga en perfectas condiciones de salud. 
          




</template>

<script>
import TituloDecorativo from '../components/TituloDecorativo.vue'
export default {
  name: 'Tema4',
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
.cont_4_1, .cont_4_1 *
  position: relative
.cont_4_1:before
  content: ''
  position: absolute
  width: 125%
  height: 70%
  top: 15%
  bottom: 15%
  left: -15%
  background: url(../assets/curso/tema4/5.png)
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
.cont_4_2
  background: url(../assets/curso/tema4/10.png)
  background-size: 100% 100%
@media screen and (max-width: 768px)
  .cont_4_2
    background: none
</style>
