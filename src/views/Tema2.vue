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
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
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
                div Ayuda a regular el pH en el intestino, pasándolo de ácido a alcalino. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Permite que el bolo se mueva a través del intestino. 
          .tarjeta.color-acento-botones.p-4(titulo="Beneficios" style="background-color:#EBEBFD;")
            h5 Beneficios
            ul.lista-ul.mt-3
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Los movimientos intestinales son estimulados, previniendo el estreñimiento. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Ayuda a remover los desechos del colon. 
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Admite un pH óptimo en el intestino, lo cual ayuda a prevenir el cáncer de colon. 
          .tarjeta.color-acento-botones.p-4(titulo="Fuentes alimentarias" style="background-color:#EBEBFD;")
            h5 Fuentes alimentarias
            ul.lista-ul.mt-3
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Linaza.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Coliflor.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Salvado de trigo.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Avena integral.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Pasta integral.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Pan integral.
              li.d-flex 
                i.fas.fa-walking(style="color:#30169A;")
                div Corteza de frutas, papas y tubérculos. 
    
    Separador

    .titulo-segundo(data-aos="flip-up")
      h2#t_2_2 2.2 Las proteínas
    
    .cont_2_2
      .row
        .col-lg-5.mb-4.mb-lg-0(data-aos="zoom-in")
          .p-4.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#D0D1FA;border-radius:15px;")
            p.mb-0 Son sustancias orgánicas que en general contienen una base de elementos químicos como carbono, hidrógeno, oxígeno y nitrógeno; también se componen por cadenas lineales de aminoácidos las cuales están encadenadas a enlaces peptídicos formados en el grupo carboxilo de un aminoácido. 
        .col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
          figure.m-auto.col-8.col-md-8.col-lg-12
            img(src="@/assets/curso/tema2/8.svg")
        .col-lg-4(data-aos="zoom-in")
          figure
            img(src="@/assets/curso/tema2/9.svg" style="max-width:80px;")
          p.mt-3.mb-0 Por añadidura son compuestos que desempeñan muchas funciones en los seres humanos, haciendo parte de tejidos, tendones, músculos, piel y uñas; además, realizan acciones metabólicas, reguladoras, transportan oxígeno, y grasas en la sangre, pertenecen al código genético (ADN), lo que define la identidad de cada persona.
      
      p.mt-4(data-aos="fade-right") A continuación, se presenta un esquema con las funciones de las proteínas.  

      .col-xl-9.m-auto.mt-4
        .row
          .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
            .p-4.h-100(style="background-color:#30169A;border-radius:15px;")
              .titulo-sexto.color-acento-contenido.text-white
                h5 Figura 1
                span Funciones de las proteínas 
              figure
                img(src="@/assets/curso/tema2/10.svg" alt="Imagen que presenta las funciones de las proteínas, la cuales son: transportadoras, reguladoras, defensivas, energéticas y plásticas o estructurales.")
          .col-lg-4(data-aos="fade-left")
            figure.m-auto.col-8.col-md-7.col-lg-12
              img(src="@/assets/curso/tema2/11.svg")
    
    Separador

    .titulo-segundo(data-aos="flip-up")
      h2#t_2_3 2.3  Las grasas o lípidos
  
    .row
      .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
        p Son sustancias que se encuentran en las células de animales o vegetales. La función más importante para el organismo de los seres humanos es dar energía al metabolismo y trasportar vitaminas liposolubles. 
        .row
          .col-lg-5.mb-4.mb-lg-0.pe-lg-0
            figure.col-10.m-auto.col-md-9.col-lg-12
              img(src="@/assets/curso/tema2/12.svg")
          .col-lg-7.ps-lg-0
            .p-4.p-lg-5.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#EFFAF4;")
              p.mb-0 Se puede decir que las grasas son un conjunto de sustancias que tienen poca solubilidad en el agua, pero sin embargo se pueden solubilizar en solventes como el éter o el cloroformo; además el medio por el cual se sintetizan es a través de los hidratos de carbono. 
        p.mt-4 Los lípidos están constituidos por colesterol libre, esterificado, triglicéridos, ácidos grasos libres y fosfolípidos, estos compuestos están presentes en las lipoproteínas plásticas y son los encargados de transportar los quilomicrones, las lipoproteínas de densidad baja (LDL) y las proteínas de alta densidad (HDL). 
      .col-lg-3(data-aos="fade-left" data-aos-delay="600")
        figure.m-auto.col-8.col-md-7.col-lg-12.d-none.d-lg-block
          img(src="@/assets/curso/tema2/13.png")
    
    .row.mt-5
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-12.col-md-10.col-lg-12
          img(src="@/assets/curso/tema2/14.png")
      .col-lg-7(data-aos="fade-left")
        p La importancia de los lípidos en la alimentación está relacionada con: 
        ul.lista-ul.mt-3.ps-4
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div Su gran aporte energético, además son el combustible metabólico. Un gramo de grasa equivale a 9 kcal. 
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div Su importante contribución a la dieta de ácidos grasos esenciales como el linoleico y el alfa-linolénico, ya que no son producidos por el organismo. 
          li.d-flex 
            i.fas.fa-walking(style="color:#30169A;")
            div El transporte de vitaminas liposolubles como la A, D, E, K que se encuentran en el organismo en bajas proporciones y que requieren de los ácidos grasos para formar lipoproteínas en las membranas celulares.

    Separador

    .titulo-segundo(data-aos="flip-up")
      h2#t_2_4 2.4 Las vitaminas

    .row
      .col-lg-5.mb-4.mb-lg-0(data-aos="zoom-in")
        .p-4.p-lg-5.h-100.d-flex.align-content-center.flex-wrap(style="background-color:#D0D1FA;border-radius:15px;")
          p.mb-0 Son sustancias orgánicas que se pueden obtener de los alimentos; igualmente son de gran importancia para el hombre porque ayudan a que el organismo se desarrolle adecuadamente. Cuando hay carencia de ellas en la dieta se pueden generar enfermedades. 
      .col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in" data-aos-delay="600")
        figure.col-8.m-auto.col-md-8.col-lg-12
          img(src="@/assets/curso/tema2/15.png")
      .col-lg-4(data-aos="zoom-in" style="place-self:end;")
        figure
          img(src="@/assets/curso/tema2/16.svg" style="max-width:80px;")
        p.mt-3.mb-0 Las vitaminas se deben suministrar al cuerpo en pequeñas cantidades, pues el organismo no puede producirlas, a excepción de algunas. 
    
    p.mt-4(data-aos="fade-right") Las vitaminas se pueden clasificar en: 

    .cont_2_3.mt-4
      .row
        .col-lg-3.mb-4.mb-lg-0(data-aos="fade-up")
          .p-4.p-xl-5.h-100(style="background-color:#FCA651;border-radius:15px;")
            figure.text-center
              img(src="@/assets/curso/tema2/18.svg" style="max-width:90px;display:inline;")
            h5.text-center.mt-3.ps-3.pe-4.m-auto.pb-1.pt-1.bg-white(style="max-width:fit-content;") Hidrosolubles
            ul.lista-ul.mt-3.m-auto
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Ácido ascórbico C. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Complejo B. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Tiamina. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Riboflavina. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Niacina. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Ácido pantoténico. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Piridoxina. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Biotina. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Ácido fólico. 
              li 
                i.fas.fa-walking(style="color:#12263F;")
                | Cobalamina. 
        .col-lg-3.mb-4.mb-lg-0(data-aos="fade-up")
          .p-4.p-xl-5.h-100(style="background-color:#30169A;border-radius:15px;")
            figure.text-center
              img(src="@/assets/curso/tema2/19.svg" style="max-width:90px;display:inline;")
            h5.text-center.mt-3.ps-3.pe-4.m-auto.pb-1.pt-1.bg-white(style="max-width:fit-content;") Liposolubles 
            ul.lista-ul.mt-3.m-auto.text-white
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Vitamina A.
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Vitamina E.
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Vitamina D.
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Vitamina K.
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Vitamina F.
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Vitámeros.
              li 
                i.fas.fa-walking(style="color:#fff;")
                | Provitamina.
        .col-lg-6(data-aos="fade-left" data-aos-delay="500")
          figure.m-auto.col-10.col-md-8.col-lg-12
            img(src="@/assets/curso/tema2/20.png")
      
      p.mt-4(data-aos="fade-right") La siguiente tabla nos presenta una comparción entre estas dos clasificaciones.
    
    .col-xl-9.m-auto.mt-4
      .titulo-sexto.color-acento-contenido(data-aos="zoom-in-down")
        h5 Tabla 1
        span Hidrosolubles versus liposolubles 
      .tabla-a.color-acento-botones
        table
          thead(style="border:0;")
            tr(style="background-color:#30169A;")
              th.text-white(style="border:0;") Ítem
              th.text-white(style="border:0;") Hidrosolubles
              th.text-white(style="border:0;") Liposolubles
          tbody
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Composición química. 
              td.text-center(style="border:1px #6063C0 solid;") Excepto la vitamina C, todas las demás contienen nitrógeno y algunas, azufre, fósforo, y cobalto. 
              td.text-center(style="border:1px #6063C0 solid;") Sólo están formados por carbono, hidrógeno y oxígeno. 
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Provitaminas. 
              td.text-center(style="border:1px #6063C0 solid;") No.
              td.text-center(style="border:1px #6063C0 solid;") Si (en algunos casos). 
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Absorción. 
              td.text-center(style="border:1px #6063C0 solid;") 
                p.mb-0 Transporte activo. 
                p.mb-0 Difusión facilitada. 
              td.text-center(style="border:1px #6063C0 solid;") 
                p.mb-0 Difusión simple. 
                p.mb-0 Presencia de grasa. 
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Transporte.
              td.text-center(style="border:1px #6063C0 solid;") Libres.
              td.text-center(style="border:1px #6063C0 solid;") Requieren las proteínas. 
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Depósito.
              td.text-center(style="border:1px #6063C0 solid;") Poco importantes. 
              td.text-center(style="border:1px #6063C0 solid;") Se almacena en tejido adiposo e hígado. 
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Necesidades. 
              td.text-center(style="border:1px #6063C0 solid;") Vía urinaria (B12, B5, ácido fólico). 
              td.text-center(style="border:1px #6063C0 solid;") Vía fecal. 
            tr.bg-white
              td.text-center(style="border:1px #6063C0 solid;") Excreción. 
              td.text-center(style="border:1px #6063C0 solid;") Se requiere en dosis frecuentes. 
              td.text-center(style="border:1px #6063C0 solid;") Se requiere en dosis periódicas. 
    
    p.mt-4(data-aos="fade-right") A continuación, se presentan las situaciones de riesgo de deficiencia vitamínica: 

    .col-xl-9.m-auto.mt-4.justify-content-center
      .row
        .col-lg-4.col-md-8.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_2_4(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4.text-center
              img(src="@/assets/curso/tema2/21.svg" style="max-width:90px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1.text-center(style="max-width:fit-content;background-color:#30169A;") Ingesta insuficiente
            ul.lista-ul.mt-3
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Alcoholismo. 
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Tercera edad. 
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Regímenes hipocalóricos.
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Vegetarianos estrictos. 
        .col-lg-4.col-md-8.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_2_4(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4.text-center
              img(src="@/assets/curso/tema2/22.svg" style="max-width:90px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1.text-center(style="max-width:fit-content;background-color:#30169A;") Necesidades metabólicas incrementadas
            ul.lista-ul.mt-3
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Embarazo y lactancia. 
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Períodos postoperatorios. 
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Enfermedades crónicas o infecciosas. 
        .col-lg-4.col-md-8.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.p-4.p-lg-4.cont_2_4(style="background-color:#EBEBFD;border-radius:15px;")
            figure.mt-4.text-center
              img(src="@/assets/curso/tema2/23.svg" style="max-width:90px;display:inline;")
            h5.mt-4.text-white.ps-3.pe-4.m-auto.pb-1.pt-1.text-center(style="max-width:fit-content;background-color:#30169A;") Interacción con medicamentos
            ul.lista-ul.mt-3
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Anticonceptivos orales, antibióticos. 
              li.d-flex
                i.fas.fa-walking(style="color:#787CF0;")
                div Situaciones de mala absorción. 
    
    .cont_2_5.mt-4
      p(data-aos="fade-right") Existen diferentes factores que pueden neutralizar o destruir las vitaminas, entre estos: 
      .row.mt-4
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure.col-9.col-md-8.col-lg-12
            img(src="@/assets/curso/tema2/25.svg")
        .col-lg-8(data-aos="fade-left")
          .tarjeta.tarjeta--azul.p-4.p-lg-5.pb-lg-4.cont_slyder1
            SlyderA(tipo="b")
              .row.mt-lg-5.mb-lg-5
                .col-lg-9.mb-4.mb-lg-0.text-white(style="place-self:center;")
                  h4 Bebidas alcohólicas 
                  p.mb-0 El alcohol disminuye el apetito en las personas y genera carencias de vitaminas B2, B3, B6 y ácido fólico. 
                .col-lg-3(style="place-self:center;")
                  figure.col-6.col-md-6.col-lg-12
                    img(src='@/assets/curso/tema2/27.svg')
              .row.mt-lg-5.mb-lg-5
                .col-lg-9.mb-4.mb-lg-0.text-white(style="place-self:center;")
                  h4 Cigarrillo
                  p.mb-0 El consumo de este producto hace que el organismo gaste más vitaminas, por ende, se recomienda incrementar la ingesta de vitamina C, debido a que ayuda a desintoxicar. 
                .col-lg-3(style="place-self:center;")
                  figure.col-6.col-md-6.col-lg-12
                    img(src='@/assets/curso/tema2/28.svg')
              .row.mt-lg-5.mb-lg-5
                .col-lg-9.mb-4.mb-lg-0.text-white(style="place-self:center;")
                  h4 Situaciones estresantes 
                  p.mb-0 Las personas bajo estrés emocional generan más adrenalina haciendo que el organismo consuma más vitamina C y produciendo la necesidad que se ingieran más vitaminas del grupo B y E.  
                .col-lg-3(style="place-self:center;")
                  figure.col-6.col-md-6.col-lg-12
                    img(src='@/assets/curso/tema2/29.svg')
              .row.mt-lg-5.mb-lg-5
                .col-lg-9.mb-4.mb-lg-0.text-white(style="place-self:center;")
                  h4 Azúcar o alimentos azucarados 
                  p.mb-0 Cuando los seres humanos consumen azúcar blanco, el cuerpo gasta muchas vitaminas para metabolizarlo, sobre todo las del grupo B1. 
                .col-lg-3(style="place-self:center;")
                  figure.col-6.col-md-6.col-lg-12
                    img(src='@/assets/curso/tema2/30.svg')
    
    Separador

    .titulo-segundo(data-aos="flip-up")
      h2#t_2_5 2.5 Los minerales
    
    p(data-aos="fade-right") Son sustancias naturales compuestas por moléculas formadas por átomos de uno o más elementos químicos. Son muy importantes para la salud del cuerpo humano, porque aportan los nutrientes necesarios para que funcione de manera correcta. 
    p(data-aos="fade-left") Los minerales se dividen en dos grupos: 
    p(data-aos="fade-up") Los #[strong(style="background-color:#95DBB3;") macroelementos], aquellos que se deben consumir en cantidades considerables: 

    .row.mt-4
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-7.col-md-7.col-lg-12
          img(src="@/assets/curso/tema2/31.png")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Calcio, potasio y magnesio ")
            p.mb-0 Forman parte de los huesos y del tejido conjuntivo, son esenciales para la circulación de la sangre. 
          .row.col-xl-11.m-auto(titulo="Fósforo ")
            p.mb-0 Este elemento en asocio con ciertos lípidos, forma los fosfolípidos, los cuales son muy importantes para la membrana celular y el tejido nervioso, también constituyen la estructura de los huesos. 
          .row.col-xl-11.m-auto(titulo="Sodio")
            p.mb-0 Es responsable de la trasmisión de impulsos nerviosos. Las necesidades de este compuesto aumentan cuando la persona suda mucho, toma diuréticos, o cuando se tienen diarreas o vómitos. 
          .row.col-xl-11.m-auto(titulo="Potasio")
            p.mb-0 Participa en la contracción del músculo cardíaco y además actúa en la regulación del balance de agua en el organismo. 
    
    .row.mt-3
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Magnesio")
            p.mb-0 Es muy importante para la asimilación de la vitamina C y el calcio, también participa en la correcta transmisión de los impulsos nerviosos. De igual manera ayuda a la buena digestión de las grasas, y a fijar el calcio. 
          .row.col-xl-11.m-auto(titulo="Cloro")
            p.mb-0 Ayuda al hígado en la eliminación de toxinas, favorece el equilibrio de ácido-base, apoya el transporte de CO2 en la sangre, y contribuye al mantenimiento de los huesos. 
          .row.col-xl-11.m-auto(titulo="Azufre")
            p.mb-0 Está presente en la composición de hormonas y vitaminas, además hace parte del cabello, de las uñas, y de la piel. 
      .col-lg-4(data-aos="fade-left")
        figure.m-auto.col-7.col-md-7.col-lg-12
          img(src="@/assets/curso/tema2/32.png")
    
    p.mt-3(data-aos="fade-right") Los #[strong(style="background-color:#95DBB3;") microelementos], aquellos que se deben consumir en cantidades mínimas: 

    .row.mt-4
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure.m-auto.col-7.col-md-7.col-lg-12
          img(src="@/assets/curso/tema2/33.png")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Hierro")
            p.mb-0 Es importante para la producción de glóbulos rojos y hemoglobina, asimismo interviene en el metabolismo celular por medio de enzimas.
          .row.col-xl-11.m-auto(titulo="Flúor")
            p.mb-0 Hace parte de la estructura de los huesos, y en los dientes aumenta la resistencia de la placa bacteriana. 
          .row.col-xl-11.m-auto(titulo="Yodo")
            p.mb-0 Ayuda a la producción de la hormona de la tiroides y al funcionamiento de los tejidos nerviosos, igualmente interviene en el crecimiento físico y mental. 
          .row.col-xl-11.m-auto(titulo="Cobre")
            p.mb-0 Contribuye a convertir el hierro almacenado en hemoglobina, además participa en la asimilación de la vitamina C. Es muy importante en la formación de huesos, tendones, sistema vascular, y tejido conectivo. 
          .row.col-xl-11.m-auto(titulo="Zinc")
            p.mb-0 Hace parte de los huesos en las enzimas anhidrasa carbónica, deshidrogenasa y carboxipeptidasa. Hace parte del proceso de producción de linfocitos y contribuye a la síntesis de proteínas. 






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
.cont_2_2, .cont_2_2 *
  position: relative
.cont_2_2:before
  content: ''
  position: absolute
  width: 125%
  height: 70%
  left: -15%
  top: 10%
  bottom: 20%
  background: url(../assets/curso/tema2/7.png)
  background-size: 100% 100%
.cont_2_3, .cont_2_3 *
  position: relative
.cont_2_3:before
  content: ''
  position: absolute
  width: 125%
  height: 85%
  left: -15%
  top: 15%
  background: url(../assets/curso/tema2/17.png)
  background-size: 100% 100%
.cont_2_4
  background: url(../assets/curso/tema1/9.png)
  background-size: 100% 100%
.cont_2_5, .cont_2_5 *
  position: relative
.cont_2_5:before
  content: ''
  position: absolute
  width: 125%
  height: 110%
  left: -15%
  top: -10%
  background: url(../assets/curso/tema2/24.png)
  background-size: 100% 100%
.cont_slyder1
  background: url(../assets/curso/tema2/26.png)
  background-size: cover
.slyder-a__btn--sigt, .slyder-a__btn--atrs
  background-color: #FCA651
  border-color: #FCA651
@media screen and (max-width: 992px)
  .cont_2_2:before, .cont_2_3:before, .cont_2_5:before
    background-size: cover
</style>
