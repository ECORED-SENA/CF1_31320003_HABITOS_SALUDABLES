<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Dieta moderada

    p(data-aos="fade-right") Consiste en hacer un control de nutrientes de la dieta. La ingesta en exceso de alimentos puede incurrir en el desarrollo de enfermedades crónicas por lo que es importante tener en cuenta: 

    .cont_5_1.mt-4
      .row.justify-content-center
        .col-lg-3.mb-4.mb-lg-0.col-md-6(data-aos="zoom-in")
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src='@/assets/curso/tema5/2.png' alt="")
            .crd_hover_txt--body(style="background-color:#30169A")
              h5.mb-3.text-white.text-center Consumo de azúcares refinados 
              p.mt-4.text-white.mb-0 Estos azúcares deben aportar menos del 10 al 15 % de la energía total consumida. 
        .col-lg-3.mb-4.mb-lg-0.col-md-6(data-aos="zoom-in")
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src='@/assets/curso/tema5/4.png' alt="")
            .crd_hover_txt--body(style="background-color:#30169A")
              h5.mb-3.text-white.text-center Grasas saturadas 
              p.mt-4.text-white.mb-0 Los ácidos grasos saturados deben aportar menos del 7 % de la energía total consumida. 
        .col-lg-3.mb-4.mb-lg-0.col-md-6(data-aos="zoom-in")
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src='@/assets/curso/tema5/3.png' alt="")
            .crd_hover_txt--body(style="background-color:#30169A")
              h5.mb-3.text-white.text-center Colesterol
              p.mt-4.text-white.mb-0 Consumir menos de 300 gramos al día. 
        .col-lg-3.mb-4.mb-lg-0.col-md-6(data-aos="zoom-in")
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src='@/assets/curso/tema5/3.png' alt="")
            .crd_hover_txt--body(style="background-color:#30169A")
              h5.mb-3.text-white.text-center Consumo de sal 
              p.mt-4.text-white.mb-0 Consumir menos de 6 gramos al día. 
      
      p.mt-5(data-aos="fade-right") Además de cumplir con rigurosidad las anteriores recomendaciones, es importante realizar una adecuada distribución de las comidas, porque de esta manera se mantiene un peso adecuado. La siguiente imagen presenta esa distribución. 

      .col-xl-9.m-auto.mt-4
        .row
          .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
            .p-4.h-100(style="background-color:#F6F6F6;border-radius:15px;")
              .titulo-sexto.color-acento-contenido
                h5 Figura 2
                span Distribución de los alimentos durante el día 
              figure
                img(src="@/assets/curso/tema5/6.svg" alt="")
          .col-lg-5(data-aos="fade-left")
            figure.m-auto.col-8.col-md-7.col-lg-12
              img(src="@/assets/curso/tema5/7.png")
    
    p.mt-5(data-aos="fade-right") Ampliemos la información sobre cada uno de ellos: 

    .row.mt-5.mb-4(data-aos="fade-right")
      .col-auto.pe-0
        .h-100(style="background-color:#95DBB3;border-radius:30px;width:23px;")
      .col
        .h-100.p-2(style="background-color:#95DBB3;max-width:fit-content;border-radius:7px;")
          h4.mb-0 Desayuno
    
    .row
      .col(style="place-self:center;" data-aos="fade-right")
        p Es la comida más importante del día, porque aporta la energía y los nutrientes que el cuerpo necesita, incluyendo el hecho que se ha tenido un ayuno prolongado durante la noche. 
        p.mb-0 Los alimentos ingeridos en la mañana deben aportar alrededor de una cuarta parte de la energía que el organismo necesita en el día.
      .col-auto.d-none.d-md-block(data-aos="fade-left")
        figure
          img(src="@/assets/curso/tema5/8.svg")
    
    p.mt-4(data-aos="fade-right")  El desayuno debe ser variado e incluir por lo menos cuatro alimentos de los diferentes grupos alimenticios: 

    .row.mt-4.mb-4
      .col-lg-6.mb-4(data-aos="fade-right")
        .row
          .col-md-auto.pe-md-0.col-9.m-auto
            figure.mb-3.mb-md-0
              img(src="@/assets/curso/tema5/9.png")
          .col-md.col-12.ps-md-0
            .h-100.p-4.d-flex.align-content-center.flex-wrap(style="background-color:#EFFAF4;border-radius:0px 5px 5px 0px;")
              p.mb-2.w-100 Leches y derivados 
              ul.lista-ul.mb-0
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Un vaso de leche con o sin chocolate, café o té. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Un yogur con o sin grasa. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Una porción de queso cuajada o curado.
      .col-lg-6.mb-4(data-aos="fade-left")
        .row
          .col-md-auto.pe-md-0.col-9.m-auto
            figure.mb-3.mb-md-0
              img(src="@/assets/curso/tema5/10.png")
          .col-md.col-12.ps-md-0
            .h-100.p-4.d-flex.align-content-center.flex-wrap(style="background-color:#EFFAF4;border-radius:0px 5px 5px 0px;")
              p.mb-2.w-100 Cereales y derivados 
              ul.lista-ul.mb-0
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Pan blanco o integral. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Galletas o tostadas. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Cereales. 
      .col-lg-6.mb-4(data-aos="fade-right")
        .row
          .col-md-auto.pe-md-0.col-9.m-auto
            figure.mb-3.mb-md-0
              img(src="@/assets/curso/tema5/11.png")
          .col-md.col-12.ps-md-0
            .h-100.p-4.d-flex.align-content-center.flex-wrap(style="background-color:#EBEBFD;border-radius:0px 5px 5px 0px;")
              p.mb-2.w-100 Frutas y hortalizas 
              ul.lista-ul.mb-0
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Frutas.
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Jugo natural de cualquier fruta. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Verduras frescas. 
      .col-lg-6.mb-4(data-aos="fade-left")
        .row
          .col-md-auto.pe-md-0.col-9.m-auto
            figure.mb-3.mb-md-0
              img(src="@/assets/curso/tema5/12.png")
          .col-md.col-12.ps-md-0
            .h-100.p-4.p-lg-3.d-flex.align-content-center.flex-wrap(style="background-color:#EBEBFD;border-radius:0px 5px 5px 0px;")
              p.mb-2.w-100 Complementos 
              ul.lista-ul.mb-0
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Aceite de oliva. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Mermelada. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Huevos.
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Frutos secos.
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Jamón.
    
    .row.mt-4
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Media mañana")
            p Es una comida que se debe consumir horas después del desayuno para así adquirir fuerzas hasta el almuerzo. Se puede comer: 
            ul.lista-ul.ps-4
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Una fruta.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Yogur o un vaso de leche. 
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Jugo de frutas.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Galletas integrales.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Un sánduche con una rebanada de tomate, jamón de pavo y pan integral. 
          .row.col-xl-11.m-auto(titulo="Almuerzo")
            p Es la segunda comida de más importancia. Debe ser muy completa de acuerdo con los grupos de alimentos, es decir, ofrecer proteínas, verduras, cereales y algún derivado lácteo; por lo general consta: 
            ul.lista-ul.ps-4
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div De un primer plato, el cual puede ser pasta, arroz o verduras. 
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div De un segundo plato, el cual puede comprender pescado, carne o pollo. 
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div De un tercer plato, el cual incluye el postre, es decir una fruta o un yogur. 
            p.mt-3 La bebida acompañante puede ser un vaso de agua o un jugo de frutas, hecho en agua bajo en azúcar. 
          .row.col-xl-11.m-auto(titulo="Media mañana")
            p Es un alimento que se consume en horas de la tarde, el cual puede ser: 
            ul.lista-ul.ps-4
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Galletas o tostadas.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Jugo.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Fruta.
          .row.col-xl-11.m-auto(titulo="Comida")
            p Es la última del día, es importante no acostarse sin comer, debe ser ligera y no muy tarde en la noche. Se recomienda consumir: 
            ul.lista-ul.ps-4
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Pescado.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Pollo.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Tortilla.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Arroz.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Pan integral.
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Verduras.
      .col-lg-4(data-aos="fade-left" data-aos-delay="500")
        figure.m-auto.col-7.col-md-7.col-lg-12
          img(src="@/assets/curso/tema5/13.svg")
    
    TituloDecorativo.mt-5(titulo="Importancia del agua en la dieta")

    .row
      .col(style="place-self:center;" data-aos="fade-right")
        p El agua es el principal componente de los seres vivos. En los seres humanos se encuentra en un 60 % en el interior de las células, el resto se halla al exterior de estas, circulando a través de la sangre y los tejidos.
        p.mb-0 Por medio del agua, las células se comunican y transportan el oxígeno y los nutrientes a los tejidos; además este líquido ayuda al cuerpo a eliminar desechos del metabolismo celular y a regular la temperatura corporal cuando se realiza ejercicio o cuando la temperatura ambiente es muy elevada. 
      .col-auto.d-none.d-md-block(data-aos="fade-left")
        figure
          img(src="@/assets/curso/tema5/14.svg")
    
    .row.mt-5
      .col-lg-5.mb-4.mb-lg-0(data-aos="zoom-in")
        .p-4.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#D0D1FA;border-radius:15px;")
          p.mb-0 El agua suministrada al organismo es la que se consume en forma de alimentos como sopas, caldos, jugos y bebidas refrescantes. Algunos alimentos como las frutas y verduras contienen un 80 % de agua, por eso estos alimentos deben considerarse siempre a la hora de mantener un buen balance hídrico. 
      .col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
        figure.m-auto.col-8.col-md-8.col-lg-12
          img(src="@/assets/curso/tema5/15.svg")
      .col-lg-4(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/tema5/16.svg" style="max-width:80px;")
        p.mt-3 Las necesidades de agua de cada persona dependen de aspectos como edad, sexo, dieta, estado físico, enfermedades, y hasta del clima. 
        p.mb-0 Generalmente se recomienda un suministro de agua de al menos ocho raciones diarias (1 ración = 1 vaso = 250 mililitros). 
    
    p.mt-4(data-aos="fade-right") La ingesta de agua es diferente en poblaciones de riesgo: 

    .row.mt-4
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-8.col-md-7.col-lg-12
          img(src="@/assets/curso/tema5/17.png")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Niños")
            p Demandan más agua que los adultos, porque están en pleno crecimiento y por ende, su organismo requiere más del preciado líquido.
          .row.col-xl-11.m-auto(titulo="Mujeres embarazadas")
            p Es importante prestar mucha atención a la hidratación de la madre según la evolución y desarrollo del feto. 
          .row.col-xl-11.m-auto(titulo="Mujeres en período lactante ")
            p Necesitan ingerir un volumen mayor de agua para así responder a la cantidad de leche requerida por el lactante. Los bebés son muy sensibles a la falta de agua, por lo que se les recomienda a las madres lactantes, consumir 3,1 litros al día. 
          .row.col-xl-11.m-auto(titulo="Los ancianos ")
            p Son muy susceptibles a deshidratarse debido a las enfermedades que pueden llegar a padecer por su edad; además, tienen pérdida de la sensación de sed, por lo que se les recomienda que consuman mínimo entre 6 a 8 raciones diarias, es decir 1,5 a 2 litros por día. 
    
    .col-xl-10.m-auto.mt-4(data-aos="zoom-in")
      .cont_5_2.p-3(style="background-color:#77AF8F;border-radius:14px;")
        .row
          .col-auto.d-none.d-md-block
            figure
              img(src="@/assets/curso/tema5/19.svg")
          .col(style="place-self:center;")
            p.mb-0 Cuando hay deshidratación, por lo general el cuerpo ya ha perdido 1 % del peso corporal; por tal razón se debe beber agua constantemente, para mantener el cuerpo hidratado. 







</template>

<script>
import TituloDecorativo from '../components/TituloDecorativo.vue'
export default {
  name: 'Tema5',
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
.cont_5_1, .cont_5_1 *
  position: relative
.cont_5_1:before
  content: ''
  position: absolute
  width: 125%
  height: 70%
  top: 15%
  bottom: 15%
  left: -15%
  background: url(../assets/curso/tema5/1.png)
  background-size: 100% 100%
.crd_hover_txt
  position: relative
  padding: 0 !important
  overflow: hidden !important
  border-radius: 10px
.crd_hover_txt .crd_hover_txt--body
  position: absolute
  padding: 1.5rem
  width: 100%
  bottom: 0
  transition: all .5s ease-in-out
  transform: translateY(calc(100% - 3.85rem))
  background-color: #fff7e6
.crd_hover_txt:hover .crd_hover_txt--body
  transition: all .5s ease-in-out
  transform: translateY(0)
  background-color: #FCA651 !important
.crd_hover_txt:hover .crd_hover_txt--body *
  color: #12263F !important
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
.cont_5_2
  background: url(../assets/curso/tema4/10.png)
  background-size: 100% 100%
@media screen and (max-width: 768px)
  .cont_5_2
    background: none
</style>
