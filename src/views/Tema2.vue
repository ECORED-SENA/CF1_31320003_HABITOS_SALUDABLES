<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Composición de los alimentos 

    .cont_2_1
      .col-xl-10.m-auto
        .p-3(style="background-color:#F1EBE0;border-radius:15px;" data-aos="zoom-in")
          .row
            .col-auto(style="place-self:center;")
              figure
                img(src="@/assets/curso/tema2/1.svg")
            .col(style="place-self:center;")
              p.mb-0 Los nutrientes presentes en los alimentos se dividen en cuatro grupos: carbohidratos, proteínas, grasas y vitaminas.
      
      Separador

      .titulo-segundo(data-aos="flip-up")
        h2#t_2_1 2.1 Carbohidratos 
      
      .row
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-9.col-md-8.col-lg-12
            img(src="@/assets/curso/tema2/2.png")
        .col-lg-8(data-aos="fade-left")
          p Los hidratos de carbono o carbohidratos son moléculas de carbono, hidrógeno y oxígeno, cuya fórmula es (CH2O)n. Se clasifican en azúcares simples, los cuales están conformados por una sola molécula, llamados monosacáridos, por los disacáridos o azúcares dobles, formados por dos moléculas, y por los polisacáridos, constituidos por 10 moléculas (considerados los azúcares más complejos). Estos compuestos se hallan en la mayoría de los alimentos y su función principal es dar energía a las personas. 
          p Otras de las funciones más importantes de los carbohidratos son: 
          ul.lista-ul.mt-3.ps-4
            li 
              i.fas.fa-walking(style="color:#30169A;")
              | Dar energía al cerebro y al sistema nervioso central para que operen adecuadamente. 
            li 
              i.fas.fa-walking(style="color:#30169A;")
              | Mantener un correcto funcionamiento de los músculos y de la presión arterial. 
            li 
              i.fas.fa-walking(style="color:#30169A;")
              | Sostener la temperatura corporal y las funciones de los órganos internos. 
            li 
              i.fas.fa-walking(style="color:#30169A;")
              | Ayudar al organismo a construir moléculas más complejas. 
      
      p.mt-4(data-aos="fade-right") Los carbohidratos se clasifican según la complejidad de su estructura molecular, así: 

      .row
        .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
            .row.col-xl-11.m-auto(titulo="Monosacáridos o azúcares simples ")
              p Están formados según el número de carbonos presentes en la molécula, los cuales pueden oscilar entre tres y seis átomos de carbono. 
              p.mb-0 Las tres hexosas más importantes en la nutrición y el metabolismo son la glucosa, la fructosa y la galactosa. La glucosa es el azúcar simple más utilizado por las células para obtener energía; la fructosa, más conocida como el azúcar de las frutas por estar presente en estas, se forma en el organismo de los seres humano en la digestión, a partir de la hidrólisis de la sacarosa y, por último, la galactosa, la cual se halla en la leche y que por medio de la digestión es liberada para que el hígado la convierta en glucosa para luego pasar a la circulación. 
            .row.col-xl-11.m-auto(titulo="Disacáridos ")
              p Están conformados por dos monosacáridos enlazados entre sí que mediante el proceso de hidrólisis en la digestión se convierten en hexosas. Los más conocidos en este grupo son la sacarosa, la lactosa y la maltosa. La lactosa es el azúcar que se encuentra en la leche de los mamíferos, asimismo está formada por una molécula de glucosa y una de galactosa. 
              p.mb-0 La sacarosa formada por una molécula de glucosa y una de fructosa, es un azúcar que se encuentra en la caña y la remolacha. La maltosa no está presente en los alimentos, sino que se genera en el organismo humano como producto de la digestión del almidón; además está formada por dos moléculas de glucosa entrelazadas entre sí. 
            .row.col-xl-11.m-auto(titulo="Polisacáridos ")
              p.mb-0 Constituidos por cadenas largas de monosacáridos, es el grupo más complejo entre los carbohidratos; se descomponen en moléculas más pequeñas por hidrólisis en el organismo de los seres humanos y tienen la función de mantener reservas de energía. Los más conocidos en este grupo son el almidón, el glucógeno, las dextrinas y la fibra dietaria. 
        .col-lg-3(data-aos="fade-left")
          figure.m-auto.col-7.col-md-7.col-lg-12
            img(src="@/assets/curso/tema2/3.png")
    
    TituloDecorativo.mt-5(titulo="Fibra dietaria")

    .row
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-10.col-md-10.col-lg-12
          img(src="@/assets/curso/tema2/4.svg")
      .col-lg-8(data-aos="fade-left")
        p La fibra es de origen vegetal y se halla en las paredes celulares de los vegetales. Bajo esta denominación se pueden incluir carbohidratos como el almidón resistente, el cual no se degrada ante las enzimas digestivas; dentro de este grupo se incluye la lignina, la cual no es un hidrato de carbono. 
        p Los componentes más conocidos de la fibra son la celulosa, la hemicelulosa, las pectinas, las gomas, el agar, los mucilagos y la lignina.
    
    p.mt-4(data-aos="fade-right") La fibra dietaria se clasifica en: 

    TituloDecorativo.mt-5(titulo="Fibra soluble")

    p(data-aos="fade-right") En este grupo se encuentran las pectinas, las gomas y el agar. Estos productos tienen la característica de disolverse con facilidad en agua formando un gel grueso. 

    .row.mt-4
      .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
        TabsA.color-acento-botones
          .tarjeta.color-acento-botones.p-4(titulo="Funciones" style="background-color:#EBEBFD;")
            h5 Funciones
            ul.lista-ul.mt-3
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Aumento del volumen y de la viscosidad del bolo. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Retraso de la digestión y enlentecimiento de la absorción intestinal. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Incremento de la absorción en los enterocitos distales. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Rebaja la demanda de insulina debido a que disminuye la liberación del polipéptido inhibidor gástrico. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Aumento del tránsito intestinal, parte de los carbohidratos se absorben mal. 
          .tarjeta.color-acento-botones.p-4(titulo="Beneficios" style="background-color:#EBEBFD;")
            h5 Beneficios
            ul.lista-ul.mt-3
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Ayuda a regular el azúcar en la sangre. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Disminuye el colesterol malo (LDL) el cual es beneficioso, pues reduce el riesgo de que las personas padezcan enfermedades cardíacas. 
          .tarjeta.color-acento-botones.p-4(titulo="Fuentes alimentarias" style="background-color:#EBEBFD;")
            h5 Fuentes alimentarias
            ul.lista-ul.mt-3
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Lentejas.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Arvejas.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Duraznos.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Naranjas.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Zanahorias.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Salvado de avena.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Cebada.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Arándano rojo.
      .col-lg-3(data-aos="fade-left")
        figure.m-auto.col-8.col-md-8.col-lg-12
          img(src="@/assets/curso/tema2/5.png")
    
    TituloDecorativo.mt-5(titulo="Fibra insoluble")

    p(data-aos="fade-right") En esta agrupación se halla la celulosa, la hemicelulosa y la lignina; la fibra insoluble no se descompone, ni se disuelve en el intestino de los seres humanos, sino que pasa al tacto gástrico casi intacta. 

    .row.mt-4
      .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-8.col-md-8.col-lg-12
          img(src="@/assets/curso/tema2/6.png")
      .col-lg-9(data-aos="fade-left")
        TabsA.color-acento-botones
          .tarjeta.color-acento-botones.p-4(titulo="Funciones" style="background-color:#EBEBFD;")
            h5 Funciones
            ul.lista-ul.mt-3
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div 




</template>

<script>
import TituloDecorativo from '../components/TituloDecorativo.vue'
export default {
  name: 'Tema2',
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
.cont_2_1, .cont_2_1 *
  position: relative
.cont_2_1:before
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
.tabs-a__tab, .tabs-a__tab:hover
  background-color: #95DBB3
</style>
