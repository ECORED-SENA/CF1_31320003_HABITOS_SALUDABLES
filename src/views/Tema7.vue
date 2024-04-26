<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 7
      h1 El valor energético de los alimentos 

    .cont_7_1
      .row
        .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
          .row
            .col-lg-5.mb-4.mb-lg-0.pe-lg-0
              figure.col-10.m-auto.col-md-9.col-lg-12
                img(src="@/assets/curso/tema7/2.svg")
            .col-lg-7.ps-lg-0
              .p-4.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#EBEBFD;")
                p.mb-0 Es la cantidad de energía que se aporta al cuerpo humano, resultante de la combustión de lípidos, proteínas y glúcidos. Esta energía es utilizada por el cuerpo para mantener la temperatura y realizar todas sus funciones, se expresa en calorías o kilocalorías. Es importante tener presente que la caloría es una medida de calor que consiste en trasferir calor físicamente para de esta manera aumentar la temperatura de un gramo de agua en 1 grado, entonces se puede decir que una kilocaloría equivale a 1000 calorías. 
          p.mt-4 La dieta de las personas adultas está entre 1000 a 5000 kilocalorías por día. Todos los nutrientes presentes en los alimentos tienen un valor energético diferente, por lo que se toman valores estándares para cada grupo. Por ejemplo, un gramo de un glúcido al quemarse libera cuatro kilocalorías, lo mismo ocurre con las proteínas que desatan cuatro kilocalorías; en cambio las grasas al quemarse generan nueve kilocalorías, por eso es que los alimentos ricos en grasas constituyen un aporte en contenido energético mayor y la reserva de energía que el cuerpo humano almacena es en forma de grasa. 
        .col-lg-3(data-aos="fade-left" data-aos-delay="500")
          figure.m-auto.col-8.col-md-7.col-lg-12
            img(src="@/assets/curso/tema7/3.png")
      
      .row.mt-4
        .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-8.col-md-7.col-lg-12.d-none.d-lg-block
            img(src="@/assets/curso/tema7/4.png")
        .col-lg-7(data-aos="fade-left")
          .h-100.p-4(style="background-color:#DAF2E4;border-radius:8px;")
            figure
              img(src="@/assets/curso/tema7/5.svg" style="max-width:90px;")
            p.mt-3.mb-0 Es importante tener claro que no todos los alimentos que se consumen se queman para producir energía, una gran parte de estos los usa el organismo para construir estructuras y facilitar las reacciones químicas para prolongar la vida. Un ejemplo de los nutrientes que no aportan energía son las fibras, las vitaminas, los minerales y los oligoelementos. 
      
      TituloDecorativo.mt-5(titulo="Tablas de composición de los alimentos")

      p(data-aos="fade-right") En las tablas de composición de un alimento, se describe cuántas kilocalorías tiene el alimento, así como proteínas, lípidos y glúcidos. Para conocer el total de calorías de un alimento, es necesario saber la proporción de gramos de cada nutriente, para luego multiplicarlo por el valor calórico, por ejemplo, una porción de helado contiene: 

      .row.mt-4
        .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
          .p-4.h-100(style="background-color:#77AF8F;border-radius:12px;")
              ul.lista-ul.mb-0
                li.d-flex
                  i.fas.fa-walking(style="color:#30169A;")
                  div Proteínas: 4, entonces se multiplica 4 g x 4 calorías =16 calorías. 
                li.d-flex
                  i.fas.fa-walking(style="color:#30169A;")
                  div Grasas: 12, es decir 12 x 9 calorías = 108 calorías. 
                li.d-flex
                  i.fas.fa-walking(style="color:#30169A;")
                  div Carbohidratos: 19, por lo tanto, se multiplica 19 x 4 = 76 calorías. 
                li.d-flex.mb-0
                  i.fas.fa-walking(style="color:#30169A;")
                  div Calorías totales: 200 calorías. 
        .col-lg-6(data-aos="fade-left")
          figure.m-auto.col-10.col-md-9.col-lg-12
            img(src="@/assets/curso/tema7/6.png")
      
      TituloDecorativo.mt-5(titulo="Tablas de composición de los alimentos")
    
    p(data-aos="fade-right") El consumo diario de energía depende de los requerimientos del cuerpo, es decir del gasto que el organismo hace para suplir sus necesidades (gasto calórico total). 
    p(data-aos="fade-left") Ahora, conozcamos los componentes del gasto calórico total: 

    .row.mt-4
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-7.col-md-6.col-lg-12
          img(src="@/assets/curso/tema7/7.png")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Metabolismo basal (TMB)")
            p Es la cantidad mínima de energía que el organismo necesita para mantenerse despierto, en reposo y cumplir todas sus actividades vitales como respiración, presión arterial, latidos del corazón, entre otros. 
            p El metabolismo basal depende de factores como: 
            ul.lista-ul.mb-0.ps-4.mt-3
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Sexo: los hombres tienen mayor metabolismo basal que las mujeres. 
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Talla: las personas altas tienen mayor metabolismo basal que las bajas. 
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Peso: entre más peso, más metabolismo basal se requiere. 
              li.d-flex
                i.fas.fa-walking(style="color:#30169A;")
                div Edad: entre más joven, el metabolismo basal es mayor debido al crecimiento. 
          .row.col-xl-11.m-auto(titulo="Mantenimiento de la temperatura corporal")
            p Este concepto tiene que ver con la temperatura del medio ambiente, pues cuando una persona está en un clima caliente, el metabolismo basal puede bajar en un 10% en relación con lugares de clima frío.
          .row.col-xl-11.m-auto(titulo="Efecto térmico de los alimentos")
            p Este factor está representado por la cantidad de energía que utiliza el cuerpo para procesos de digestión, absorción, metabolismo y almacenamiento de nutrientes. Los procesos mencionados anteriormente ocupan un 10 % de la energía total consumida diariamente. 
          .row.col-xl-11.m-auto(titulo="Actividad física")
            p Factor representado por la energía utilizada durante el ejercicio físico voluntario o por diversos movimientos. 
            p El requerimiento diario de energía se establece al sumar los siguientes factores: metabolismo basal, efecto térmico de los alimentos y la actividad física. 
          .row.col-xl-11.m-auto(titulo="Gasto energético total")
            p Es importante conocer el gasto energético diario para así saber lo que en realidad el cuerpo necesita, porque a veces la dieta tiene un desequilibrio en nutrientes. Por ejemplo, cuando se consumen más calorías de las que se necesitan, el organismo las almacena en forma de grasa, ocasionando un aumento de peso. 
    
    h5.mt-4(style="color:#30169A;" data-aos="fade-up") Método FAO/OMS/UNU (1985) 
    p.mt-4(data-aos="fade-right") Las ecuaciones empleadas para calcular el gasto energético en reposo, elaboradas por expertos de la Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO), Universidad de Naciones Unidas (UNU) y la Organización Mundial de la Salud (OMS) se presentan en las siguientes tablas: 

    .col-xl-10.m-auto.mt-4
      .row
        .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            h5 Tabla 2
            span Ecuaciones para estimar el gasto energético en reposo (GER) de sujetos sanos
          .tabla-a.color-acento-botones
            table
              caption.mt-2.fw-normal(style="background-color:#F6F6F6;") Nota. Iñarritu (s.f.) 
              thead(style="border:0;")
                tr(style="background-color:#30169A;")
                  th.text-white(style="border:0;") Edad
                  th.text-white(style="border:0;") Varones
                  th.text-white(style="border:0;") Mujeres
              tbody
                tr.bg-white
                  td.text-center.fw-bold(style="border:1px #6063C0 solid;") (años)
                  td.text-center.fw-bold(style="border:1px #6063C0 solid;") kcal / día 
                  td.text-center.fw-bold(style="border:1px #6063C0 solid;") kcal / día
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 0 - 3
                  td.text-center(style="border:1px #6063C0 solid;") (60,9 x P) – 54  
                  td.text-center(style="border:1px #6063C0 solid;") (61,0 x P) - 51 
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 3 - 10 
                  td.text-center(style="border:1px #6063C0 solid;")  (22,7 x P) + 495 
                  td.text-center(style="border:1px #6063C0 solid;") (22,5 x P) + 499 
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 10 - 18
                  td.text-center(style="border:1px #6063C0 solid;")  (17,5 x P) + 651 
                  td.text-center(style="border:1px #6063C0 solid;") (12,2 x P) + 746 
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 18 - 30
                  td.text-center(style="border:1px #6063C0 solid;")  (15,3 x P) + 679 
                  td.text-center(style="border:1px #6063C0 solid;") (14,7 x P) + 496 
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 30 - 60
                  td.text-center(style="border:1px #6063C0 solid;")  (11,5 x P) + 879 
                  td.text-center(style="border:1px #6063C0 solid;") (8,7 x P) + 829 
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") > 60
                  td.text-center(style="border:1px #6063C0 solid;")  (13,5 x P) + 487 
                  td.text-center(style="border:1px #6063C0 solid;") (10,5 x P) + 596 
        .col-lg-2.mb-4.mb-lg-0(data-aos="zoom-in")
          .p-4(style="background-color:#DAF2E4;")
            p.mb-0 P: peso corporal en kilogramos. 
            p.mb-0 kcal: kilocalorías. 
        .col-lg-5(data-aos="fade-left")
          .titulo-sexto.color-acento-contenido
            h5 Tabla 3
            span Factores para estimar las necesidades energéticas diarias totales en diversos niveles de actividad general para mujeres y hombres entre 19 y 50 años
          .tabla-a.color-acento-botones
            table
              caption.mt-2.fw-normal(style="background-color:#F6F6F6;") Nota. Iñarritu (s.f.) 
              thead(style="border:0;")
                tr(style="background-color:#30169A;")
                  th.text-white.text-center(style="border:0;" colspan="2") Nivel general de actividad - factor de actividad (x GER) 
              tbody
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 
                    p.mb-0.fw-bold Muy leve
                    p.mb-0 Hombres: 1,3.
                    p.mb-0 Mujeres: 1,3.
                  td.text-center(style="border:1px #6063C0 solid;") 
                    p.mb-0.fw-bold Leve
                    p.mb-0 Hombres: 1,6.
                    p.mb-0 Mujeres: 1,5.
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;") 
                    p.mb-0.fw-bold Moderado
                    p.mb-0 Hombres: 1,7.
                    p.mb-0 Mujeres: 1,6.
                  td.text-center(style="border:1px #6063C0 solid;") 
                    p.mb-0.fw-bold Intenso
                    p.mb-0 Hombres: 2,1.
                    p.mb-0 Mujeres: 1,9.
                tr.bg-white
                  td.text-center(style="border:1px #6063C0 solid;" colspan="2") 
                    p.mb-0.fw-bold Excepcional
                    p.mb-0 Hombres: 2,4.
    
    p.mt-5(data-aos="fade-right") Ahora, conozcamos las actividades relacionadas con cada nivel de actividad: 

    .row.mt-4
      .col-lg.mb-4.mb-lg-0.pe-lg-0(data-aos="fade-right")
        .h-100.p-4(style="background-color:#DAF2E4;border-radius:9px 0px 0px 9px;")
          ul.lista-ul.mb-0
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong(style="color:#30169A;") Actividad muy leve:] diversas labores, ya sea sentado o de pie, por ejemplo, pintar, manejar, trabajo de laboratorio, computación, coser, planchar, cocinar, jugar cartas, tocar un instrumento musical, entre otros. 
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong(style="color:#30169A;") Actividad leve:] caminar, trabajos eléctricos, mesero, limpieza de casa, cuidado de los niños, golf, tenis de mesa, entre otros. 
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong(style="color:#30169A;") Actividad moderada:] andar vigorosamente, cortar el pasto, bailar, ciclismo en superficie plana, esquiar, tenis, llevar una carga, entre otros. 
            li.d-flex
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong(style="color:#30169A;") Actividad intensa:] trasladarse con carga en una pendiente, tala de árboles, excavación manual intensa, basquetbol, escalar, fútbol, correr, natación, ciclismo en cuesta, aeróbicos, entre otros. 
            li.d-flex.mb-0
              i.fas.fa-walking(style="color:#30169A;")
              div #[strong(style="color:#30169A;") Excepcional:] atletas de alto rendimiento. 
      .col-lg-auto.ps-lg-0(data-aos="fade-left")
        figure.m-auto.col-8.col-md-7.col-lg-12
          img(src="@/assets/curso/tema7/8.png")
    
    .cont_7_2.mt-4
      p(data-aos="fade-right") Ahora, para calcular el gasto energético en reposo, se puede utilizar el método de la Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO), de la Universidad de Naciones Unidas (UNU) y de la Organización Mundial de la Salud (OMS): 
      .row.mt-4
        .col-lg-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-8.col-md-7.col-lg-12
            img(src="@/assets/curso/tema7/10.png")
        .col-lg-8(data-aos="fade-left")
          .p-3.p-lg-2.mb-3(style="background-color:#6063C0;border-radius:9px;")
            .row
              .col-auto
                figure
                  img(src="@/assets/curso/tema7/11.svg")
              .col(style="place-self:center;")
                p.mb-0.text-white 1. Se calcula el gasto energético reposo (GER) con las ecuaciones de la FAO, de la OMS y de la UNU; allí está incluido el efecto térmico de los alimentos.
          .p-3.p-lg-2(style="background-color:#6063C0;border-radius:9px;")
            .row
              .col-auto
                figure
                  img(src="@/assets/curso/tema7/12.svg")
              .col(style="place-self:center;")
                p.mb-0.text-white 2. El gasto energético en reposo (GER) se multiplica por la constante del factor de actividad física teniendo en cuenta la tabla 2. 
      
      TituloDecorativo.mt-5(titulo="Ejercicio de gasto energético total (GET)")

      p(data-aos="fade-left") Si se toma el caso de una dieta en una mujer de 30 años que mide 1.59 metros, que pesa 55 kg, y cuyo índice de masa corporal (IMC) es de 20 (adecuado); asimismo realiza actividad física leve, pues es profesora de una universidad y en las tardes siempre regresa a su casa caminando en un recorrido que dura 20 minutos, ¿cuál sería el gasto energético en reposo? 

      .row.mt-4
        .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
          figure.m-auto.col-7.col-md-8.col-lg-12
            img(src="@/assets/curso/tema7/13.png")
        .col-lg-9(data-aos="fade-left")
          p #[strong Gasto energético en reposo (GER):] para hallar el gasto energético en reposo se debe tener en cuenta la tabla 1, donde la ecuación para estimar el gasto energético para una mujer de 30 años es: 
          .p-3.text-white(style="background-color:#30169A;border-radius:9px;max-width:fit-content;")
            p.mb-0 Ecuación gasto energético en reposo (GER) = 14,7 x P + 496 
            p.mb-0 = 14,7 x 55 + 496 
            p.mb-0 = 1304 kilocalorías 
          p.mt-4 Para hallar el gasto energético en reposo por la actividad física, es necesario tener en cuenta el valor para actividad física leve descrito en la tabla 2: 
          .p-3.mt-3(style="background-color:#95DBB3;border-radius:9px;max-width:fit-content;")
            p.mb-0 Gasto energético en reposo (GER) x factor de actividad física #[br] leve = 1304 x 1,5 = 1956 kilocalorías 
            p.mb-0 Luego el gasto energético total (GET) = 1950 kilocalorías / día 







</template>

<script>
import TituloDecorativo from '../components/TituloDecorativo.vue'
export default {
  name: 'Tema7',
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
.cont_7_1, .cont_7_1 *
  position: relative
.cont_7_1:before
  content: ''
  position: absolute
  width: 125%
  height: 85%
  top: 15%
  left: -15%
  background: url(../assets/curso/tema7/1.png)
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
.cont_7_2, .cont_7_2 *
  position: relative
.cont_7_2:before
  content: ''
  position: absolute
  width: 125%
  height: 100%
  left: -15%
  background: url(../assets/curso/tema7/9.png)
  background-size: 100% 100%
</style>
