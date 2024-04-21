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

    TabsC.color-acento-botones.mt-4
      .py-3.py-md-4(titulo="Carne")
        .row.col-xl-11.m-auto
          .col-lg-8.mb-4.mb-lg-0
            h5(style="color:#30169A;") Carne
            p La carne es un alimento que tiene entre 16 a 22 % de proteínas, también ostenta minerales como hierro, fósforo, magnesio, potasio, y vitaminas como B1, B2, B6, B12, ácido fólico, y niacina; además contiene grasa, la cual varía entre 4 a 25 %. 
            p Según el contenido de grasas las carnes se clasifican en: 
            ul.lista-ul.mb-0
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Magras:] si aportan más o menos 6 gramos por 100 gramos del alimento. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Semigrasas:] si brindan entre 6 a 12 gramos por 100 gramos del alimento. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Grasas:] si aportan más o menos 12 gramos de grasa por 100 gramos del alimento. 
          .col-lg-4
            figure.m-auto.col-10.col-md-9.col-lg-12
              img(src='@/assets/curso/tema3/6.png')
      .py-3.py-md-4(titulo="Pescados")
        .row.col-xl-11.m-auto
          .col-lg-8.mb-4.mb-lg-0
            h5(style="color:#30169A;") Pescados
            p Abarcan un alto valor nutritivo, su aporte de proteína es de 18 a 20 % con elevada utilidad biológica. Dentro de sus componentes está el fósforo, el calcio, la tiamina y la riboflavina, asimismo, el ácido graso presente en algunos pescados es poliinsaturado como el Omega 3. 
            p La clasificación del pescado va de acuerdo a su contenido lipídico, es decir: 
            ul.lista-ul.mb-0
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Azules o grasos:] en este grupo se hallan el emperador, el atún, el salmón y la anguila, todos con un contenido lipídico del 10 %. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Magros o blancos:] en esta asociación se encuentran la merluza, el lenguado, el bacalao, el gallo y el rape, todos con un contenido lipídico de más o menos el 5 %. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Variedad intermedia:] en esta sección se hallan la sardina, el boquerón, la caballa y el arenque, todos con contenido lipídico del 5 %.
          .col-lg-4
            figure.m-auto.col-10.col-md-9.col-lg-12
              img(src='@/assets/curso/tema3/7.png')
      .py-3.py-md-4(titulo="Mariscos")
        .row.col-xl-11.m-auto
          .col-lg-8.mb-4.mb-lg-0
            h5(style="color:#30169A;") Mariscos
            p Son los crustáceos como la langosta, el langostino, la gamba, el centollo y la cigala. Estas especies tienen poca grasa poliinsaturada y poseen más colesterol. 
            p Dentro de los mariscos también se encuentran los moluscos como las ostras, la navaja, el mejillón, el berberecho, la almeja y el caracol, los cuales ostentan bajos porcentajes de colesterol. 
          .col-lg-4
            figure.m-auto.col-10.col-md-9.col-lg-12
              img(src='@/assets/curso/tema3/8.png')
      .py-3.py-md-4(titulo="Huevos")
        .row.col-xl-11.m-auto
          .col-lg-8.mb-4.mb-lg-0
            h5(style="color:#30169A;") Huevos
            p Alimento rico en nutrientes esenciales, está constituido por: 
            ul.lista-ul.mb-0
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Clara:] compuesta por albúmina, encierra casi la mayoría de las proteínas del huevo. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div #[strong(style="color:#30169A;") Yema:] contiene proteínas, vitaminas y minerales como el fósforo y el azufre. Es rica en grasa saturada, monoinsaturada, poliinsaturada y en colesterol. 
          .col-lg-4
            figure.m-auto.col-10.col-md-9.col-lg-12
              img(src='@/assets/curso/tema3/9.png')
    
    .cont_3_1.mt-5
      p(data-aos="fade-right") Continuemos con el estudio de otros grupos de alimentos. 
      .row
        .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
            .row.col-xl-11.m-auto(titulo="Legumbres")
              .col-lg-5.mb-4.mb-lg-0
                figure.m-auto.col-12.col-md-10.col-lg-12
                  img(src="@/assets/curso/tema3/11.png")
              .col-lg-7
                p Se caracterizan por tener un alto porcentaje proteico, contienen además carbohidratos, vitaminas del grupo B y minerales como calcio, hierro y magnesio. 
                p Son ricas en fibra, en este grupo se encuentran las lentejas, los frijoles, los garbanzos y la soya. 
            .row.col-xl-11.m-auto(titulo="Tubérculos")
              .col-lg-5.mb-4.mb-lg-0
                figure.m-auto.col-12.col-md-10.col-lg-12
                  img(src="@/assets/curso/tema3/12.png")
              .col-lg-7
                p Contienen macro y micronutrientes, después de su cosecha abarcan en promedio 80 % de agua y un 20 % de materia seca (almidón). En este grupo se encuentra la papa, rica en lisina y en carbohidratos como el almidón, incluyendo un pequeño porcentaje de sacarosa, fructosa y glucosa. 
            .row.col-xl-11.m-auto(titulo="Frutos secos")
              .col-lg-5.mb-4.mb-lg-0
                figure.m-auto.col-12.col-md-10.col-lg-12
                  img(src="@/assets/curso/tema3/13.png")
              .col-lg-7
                p En este grupo se hallan las almendras, castañas, nueces, avellanas, semillas de girasol y los pistachos; estos frutos se caracterizan por ser ricos en proteínas, además contienen grasas como las poliinsaturadas y carbohidratos. 
            .row.col-xl-11.m-auto(titulo="Verduras y hortalizas")
              .col-lg-5.mb-4.mb-lg-0
                figure.m-auto.col-12.col-md-10.col-lg-12
                  img(src="@/assets/curso/tema3/14.png")
              .col-lg-7
                p Están formadas por carbohidratos (polisacáridos), proteínas, agua, vitaminas y minerales. Son ricas en fibra dietaria, además contienen antioxidantes y polifenoles. 
                p Su composición depende en mayor parte, del suelo donde son cultivadas. 
            .row.col-xl-11.m-auto(titulo="Frutas")
              .col-lg-5.mb-4.mb-lg-0
                figure.m-auto.col-12.col-md-10.col-lg-12
                  img(src="@/assets/curso/tema3/15.png")
              .col-lg-7
                p Tienen porcentajes de agua de 80 a 95 % en su composición. Gozan de carbohidratos como el almidón, de azúcares, de celulosa y hemicelulosa, incluyendo además proteínas en baja proporción. 
                p En las frutas, vitaminas como la B se halla en pocas cantidades, contrario a la vitamina A, la cual se encuentra en frutas amarillas como el melón y el durazno, mientras que la vitamina C está en mayor proporción en cítricos como la naranja, la mandarina y el limón. 
        .col-lg-3(data-aos="fade-left" data-aos-delay="700")
          figure.m-auto.col-7.col-md-7.col-lg-12
            img(src="@/assets/curso/tema3/16.svg")
      
      TituloDecorativo.mt-5(titulo="Cereales y derivados")

    p(data-aos="fade-right") Están compuestos por carbohidratos (6-12 %), proteínas, grasas (1-5 %). Son ricos en minerales como hierro, potasio, fósforo y vitaminas del complejo B. Si estos alimentos se consumen en forma integral, su aporte en fibra será mayor. 
    .row.mt-4
      .col-lg-6.mb-4.mb-lg-0.pe-lg-0(data-aos="fade-right")
        .p-4.p-lg-5.h-100(style="background-color:#EBEBFD;border-radius:15px 0px 0px 15px;")
          .row(data-aos="zoom-in-down" data-aos-delay="300")
            .col-auto.pe-0
              figure
                img(src="@/assets/curso/tema3/17.svg")
            .col.ps-1(style="place-self:end;")
              h5.mb-0.ps-3.pe-3.pt-1.pb-1.text-white(style="background-color:#30169A;max-width:fit-content;") Arroz
          p.mt-4 Cereal rico en carbohidratos, es el más consumido del planeta. 
          p El arroz integral contiene vitamina E, B y fibra, mientras que el arroz molido y sin cascarilla, pierde entre un 50 % de los minerales y un 80 % de las vitaminas liposolubles. 
      .col-lg-6.mb-4.mb-lg-0.ps-lg-0(data-aos="fade-left")
        .p-4.p-lg-5.h-100(style="background-color:#95DBB3;border-radius:0px 15px 15px 0px;")
          .row(data-aos="zoom-in-down" data-aos-delay="300")
            .col-auto.pe-0
              figure
                img(src="@/assets/curso/tema3/18.svg")
            .col.ps-1(style="place-self:end;")
              h5.mb-0.ps-3.pe-3.pt-1.pb-1.text-white(style="background-color:#30169A;max-width:fit-content;") Maíz
          p.mt-4 Este cereal es muy importante, porque es uno de los más consumidos en el mundo, contiene carbohidratos, vitaminas, minerales y carotenos en altos porcentajes. 
          p El maíz no tiene gluten, haciéndolo un alimento perfecto para los celiacos.
    
    TituloDecorativo.mt-5(titulo="Grasas")

    .row.mt-4
      .col-lg-4.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
        .h-100.p-4.p-lg-4.cont_3_2.text-center(style="background-color:#DAF2E4;border-radius:15px;")
          figure.mt-4
            img(src="@/assets/curso/tema3/20.svg" style="max-width:100px;display:inline;")
          h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Margarina
          p.mt-3 Producto constituido por grasas hidrogenadas de configuración trans. Las margarinas light tienen 40 % de grasa. 
      .col-lg-4.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
        .h-100.p-4.p-lg-4.cont_3_2.text-center(style="background-color:#DAF2E4;border-radius:15px;")
          figure.mt-4
            img(src="@/assets/curso/tema3/21.svg" style="max-width:100px;display:inline;")
          h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Aceite de oliva 
          p.mt-3 Extraído como su nombre lo dice, de las olivas. Está compuesto por ácidos grasos monoinsaturados en mayor cantidad y poliinsaturados en menor cuantía; presenta un alto valor energético y está catalogado como un alimento funcional. 
      .col-lg-4.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in")
        .h-100.p-4.p-lg-4.cont_3_2.text-center(style="background-color:#DAF2E4;border-radius:15px;")
          figure.mt-4
            img(src="@/assets/curso/tema3/22.svg" style="max-width:100px;display:inline;")
          h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1(style="max-width:fit-content;background-color:#30169A;") Aceite de girasol, maíz y soya
          p.mt-3 Estos aceites provienen de vegetales y contienen un alto contenido de linolénico y vitamina E. 





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
.tabs-c__content-item
  background-color: #EBEBFD
  padding-top: 1rem
.tabs-c__header
  margin-bottom: 0px
.tabs-c__tab.py-3.tabs-c__tab--active span
  font-weight: bold
.tabs-c__tab
  border-bottom: 4px solid #30169A
.cont_3_1, .cont_3_1 *
  position: relative
.cont_3_1:before
  content: ''
  position: absolute
  width: 125%
  height: 100%
  left: -15%
  background: url(../assets/curso/tema3/10.png)
  background-size: 100% 100%
.cont_3_2
  background: url(../assets/curso/tema3/19.png)
  background-size: 100% 100%
@media screen and (max-width: 992px)
  .cont_3_1:before
    background-size: cover
</style>
