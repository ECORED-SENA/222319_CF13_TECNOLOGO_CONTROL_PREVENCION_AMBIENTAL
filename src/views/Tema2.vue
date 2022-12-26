<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Aprovechamiento y tratamiento de los residuos sólidos no peligrosos 

    p.mb-4 El proceso de aprovechamiento de residuos sólidos no peligrosos se genera, principalmente, con papel, cartón, vidrio, metal, plástico. 
    
    .bloque-texto-g.color-acento-contenido.p-4.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Tal proceso de aprovechamiento se da cuando los materiales sobrantes o descartados de cualquier proceso productivo son restituidos o acondicionados para nuevos servicios que, además, son favorables al ambiente. Por lo general, el aprovechamiento de los residuos se da mediante la reutilización y el reciclaje.
    separador 

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.1 Papel y cartón

    .row.align-items-center.mb-4
      .col-lg-6
        .tarjeta.color-1.p-5
          p.mb-0 El papel y el cartón son productos que se requieren para comunicación de información, trasmisión de conocimiento y cultura, empacar, transportar, y un sinnúmero de actividades de la vida diaria. En Colombia, el papel es producido a partir de fibras de celulosa obtenidas del bagazo de la caña de azúcar - residuo resultado de un proceso agroindustrial - o de madera proveniente de plantaciones forestales certificadas de pino y eucalipto, que son cosechadas y renovadas con fines comerciales, tal como se hace con otros cultivos agrícolas. Estas dos fuentes de celulosa tienen la gran ventaja de provenir de un recurso renovable, que también es reciclable y biodegradable.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')

    .row.justify-content-center.mb-4
      .col-lg-10
        h4 Vida útil y nueva vida
        p.mb-4 El reciclaje prolonga la vida útil de las fibras de celulosa al permitir que productos que ya han cumplido su vida útil se puedan utilizar como materia prima en la elaboración de nuevos papeles o cartones, convirtiéndose en otra fuente importante de abastecimiento de fibra de la industria papelera colombiana. 
        .row.align-items-center
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/img3.jpg', alt='Texto que describa la imagen')
          .col-lg-7
            .tarjeta.color-2.p-4.mb-4
              h4 Colombia responsable
              p.mb-0 El reciclaje de papel en Colombia inició en los años 40, cuando las empresas productoras de cajas de cartón adecuaron su proceso productivo para incorporar desperdicios de cartón como insumo. La tendencia de recuperación de papel desde ese entonces ha sido creciente, alcanzando en los últimos 5 años un índice de recolección promedio del 47% del papel consumido.
            h4 Reducción de necesidades y de consumo
            p.mb-0 Con él, se reducen las necesidades de fibra virgen y, por lo tanto, las de los insumos y materias primas utilizados para producirla. Sin embargo, el reciclaje de las fibras de celulosa no es infinito, ya que en los procesos de repulpeo y refinación las fibras van perdiendo propiedades como longitud y resistencia, por lo que es necesario mezclarlas con fibra virgen para la producción de algunos productos.
    h4 Muy importante
    p.mb-4 El papel debe almacenarse en instalaciones cerradas con el fin de que no se altere su calidad ni adquiera humedad. Cuando el material es recibido en la bodega, se debe medir la humedad con un higrómetro, esta no debe pasar del 10%, ya que cualquier papel o cartón con un porcentaje adicional será descartado.

    .bg_grad-02
      .row.justify-content-center.mb-4 
        .col-lg-10.mb-4
          h5.mb-0 Figura 1
          span Ciclo del papel y cartón
        .row.justify-content-center
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema2/img4.jpg', alt='Texto que describa la imagen')
            figcaption Nota. ANDI (2017) Calidades de materiales para reciclaje. p.7
      br
      h4 Perjudicial
      p.mb-4 Se consideran elementos perjudiciales para el proceso de reciclaje aquellos no fibrosos que deterioran la calidad del papel y el cartón, y que, además, perjudican el proceso productivo, los equipos y el producto final: trapos, plásticos, cauchos, hule, poliestireno expandido, vidrios, colillas de cigarrillo, residuos de aceites, deshechos de comidas, pinturas no solubles, humedad excesiva cuerdas de todo tipo, alambre, zunchos, metales de todo tipo, cabuyas, piedras, arena, madera, tierra o barro, residuos de cemento, papel alquitrán, de seguridad, químico, moneda, carbón, encerados, celofán, glassine, de fotografía, químico, papeles impregnados de parafina, de negro humo, de grasa, aceite o manteca.

    .row.align-items-center.mb-4 
      .col-lg-6
        .tarjeta.color-3.p-5
          h4 De sumo cuidado
          p.mb-0 Es importantísimo que, en el proceso de reciclaje, los papeles no estén revestidos de plástico o con satinados plásticos, de cera, aluminio, barniz o laca, papeles con resistencia en húmedo o con barnizado resistentes a la humedad, papeles adhesivos con alma de tela o plástico, papeles o cintas con adhesivos no solubles en agua, moños o lomos con cualquier pegante, papeles laminados con aluminio u otros materiales, papeles deteriorados por acción nociva del tiempo, papeles artificiales elaborados a partir de plásticos o polímeros, canastas, bandejas o separadores de empaques para huevos o frutas.
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema2/img5.jpg', alt='Texto que describa la imagen')

    h4 Entre muchos beneficios
    p.mb-4 En la fabricación del papel, cada vez que se sustituye 1 kg de fibras vírgenes para papel y cartón reciclado, se ahorran 2,3 kg de CO2 equivalente, lo que corresponde a recorrer una distancia de 13,501 km con un vehículo.

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-8
              .row.mb-2
                .col-lg-2
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-10
                  p.mb-0 Para profundizar en este punto del contenido, se le invita a estudiar el Anexo_1_Tabla1_CategoriaDeReciclajePapelCarton, y a observar cuidadosamente los videos que se proponen en los siguientes enlaces:
              .row
                .col-lg-1
                .col-lg-8
                  a.anexo.mb-3(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-pdf.svg")
                    .anexo__texto
                      p <b>Anexo.</b> Tabla1_CategoriaDeReciclajePapelCarton
                  
                  a.anexo.mb-3(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p <b>Enlace web.</b>> Edar Osorio (2018, 12 abril) Cómo se hace el papel reciclado  
                    
                  a.anexo.mb-3(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p <b>Enlace web.</b>> KimberlyClarkPeru (2011, 22 agosto) Proceso de reciclaje de papel
                    
            .col-lg-4 
              figure.mb-2
                img(src='@/assets/curso/tema2/1.png', alt='Texto que describa la imagen')
    separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.2 Plásticos

    p.mb-4 El plástico es un material sólido sintético, llamado polímero, que puede ser moldeado mediante calor y/o presión y cuyo componente principal es el carbono. Hay una gran variedad de clases de plástico, dependiendo de su composición, y este factor es fundamental cuando se lleva a cabo el reciclaje de plástico. Los plásticos se clasifican en tres grupos, según la disposición de las macromoléculas que los constituyen.

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-5.p-4
          .row.mb-4
            .col-lg-6
              figure.mb-2
                img(src='@/assets/curso/tema2/img6.jpg', alt='Texto que describa la imagen')
              h4.text-center Termoplásticos
              p.mb-0.text-center es un plástico que, a temperatura ambiente, es plástico o deformable, se convierte en un líquido cuando se calienta y se endurece en un estado vítreo cuando se enfría suficiente.
            .col-lg-6
              figure.mb-2
                img(src='@/assets/curso/tema2/img7.jpg', alt='Texto que describa la imagen')
              h4.text-center Termoestables
              p.mb-0.text-center son materiales que, una vez que han sufrido el proceso de calentamiento-fusión y formación-solidificación, se convierten en materiales rígidos que no vuelven a fundirse. 
          h4 Identificación
          p.mb-3 Por otra parte, se estableció un sistema de clasificación para facilitar la identificación de los plásticos, esto se reconoce al mirar la pieza de plástico: se encuentra el símbolo del reciclaje más un número. 
          p.mb-0 De esta manera, se facilita mucho el reciclaje del plástico, al identificar rápidamente y sin errores el tipo de polímero de que se trata. 
        figcaption Recytrans (2013) ¿Cómo se recicla el plástico? - https://www.recytrans.com/blog/como-se-recicla-el-plastico/
    p.mb-4 En relación directa con lo anteriormente dicho, los requisitos que debe cumplir un residuo plástico para ser reciclado son:

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-6.p-4.mb-2
          .row 
            .col-lg-4
              figure
                img(src='@/assets/curso/tema2/img8.jpg', alt='Texto que describa la imagen')
            .col-lg-8
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  p.mb-0 No haber estado en contacto con sustancias tóxicas, como agroquímicos o residuos peligrosos ni con bacterias patógenas.
                li 
                  i.fas.fa-check
                  p.mb-0 Sus propiedades mecánicas no deben estar deterioradas.
                li 
                  i.fas.fa-check
                  p.mb-0 Separar los residuos plásticos de acuerdo con su forma: envases, bolsas y pastas.
                li 
                  i.fas.fa-check
                  p.mb-0 Separar las etiquetas, tapas y eliminar materiales extraños, como ganchos o residuos de comida.
                li 
                  i.fas.fa-check
                  p.mb-0 Clasificar los materiales según sea el tipo de polímero (1 al 7).
                li 
                  i.fas.fa-check
                  p.mb-0 Lavar el material, pero no se debe utilizar soda cáustica, detergentes o solventes fuertes; se debe escurrir y secar el material plástico, y controlar la calidad de las resinas recuperadas.
                li 
                  i.fas.fa-check
                  p.mb-0 Molerlo, según el tipo de polímero (opcional).
                li 
                  i.fas.fa-check
                  p.mb-0 Almacenar en sitios cubiertos y con poca humedad.
                li 
                  i.fas.fa-check
                  p.mb-0 Los pegantes se deben retirar del producto recuperado.
                li 
                  i.fas.fa-check
                  p.mb-0 Se deben evitar materiales o productos impresos.
                li 
                  i.fas.fa-check
                  p.mb-0 Preferiblemente, no deben tener grasas u otros materiales viscosos.    
        figcaption Recytrans (2013) ¿Cómo se recicla el plástico? - https://www.recytrans.com/blog/como-se-recicla-el-plastico/

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-8
              .row.mb-2
                .col-lg-2
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-10
                  p.mb-0 Se le solicita ver el Anexo_2_Tabla2_TiposPolimeroPlasticos. Asimismo, y para mayor asimilación de los contenidos, visualice los videos que se proponen en los siguientes enlaces: 
              .row
                .col-lg-1
                .col-lg-8
                  a.anexo.mb-3(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-pdf.svg")
                    .anexo__texto
                      p <b>Anexo.</b> 2_Tabla2_TiposPolimeroPlasticos
                  
                  a.anexo.mb-3(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p <b>Enlace web.</b>> Fomentar aprovechamiento de residuos sólidos (2017,15 mayo) Reciclaje del plástico y proceso de producción.  

                  a.anexo.mb-3(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p <b>Enlace web.</b>> The Coca-Cola Co. (2018, 23 noviembre) El paso a paso en el reciclaje de una botella PET.
                    
            .col-lg-4 
              figure.mb-2
                img(src='@/assets/curso/tema2/2.png', alt='Texto que describa la imagen')
    separador

    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.3 Tetra Pak
    
    .bloque-texto-g.color-acento-contenido.p-4.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img9.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 <b>El principal objetivo ambiental del Tetra Pak es minimizar los impactos ambientales de sus productos a lo largo de todo su ciclo de vida,</b> haciendo un uso eficiente de recursos en el desarrollo y diseño de los mismos, en sus procesos de manufactura y en sus operaciones.

    TabsA.color-acento-contenido.mb-4
      .tarjeta.color-7.p-4(titulo="Materias primas renovables")
        h4 Materias primas renovables
        .row.align-items-center
          .col-lg-2
            figure
              img(src='@/assets/curso/tema2/icon.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p El Tetra Pak busca que sus envases provengan en un 100% de materias primas renovables, para lo cual trabaja de la mano con los proveedores de pulpa (donde el objetivo es que todos tengan certificación FSCTM), de aluminio y plástico. Igualmente, todas las acciones de diseño de nuevos envases y sistemas de llenado buscan que estos sean más eficientes, reciclables y con mayor porcentaje de materiales; todas las plantas a nivel mundial están certificadas con la norma ISO 14001, enfocándose en programas de reducción, minimización, mitigación y compensación de impactos ambientales en el proceso productivo.

      .tarjeta.color-7.p-4(titulo="En cuanto a reciclaje")
        h4 En cuanto a reciclaje
        .row.align-items-center
          .col-lg-2
            figure
              img(src='@/assets/curso/tema2/icon.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p Tetra Pak® está invirtiendo en la colocación de equipos en la industria papelera y de aglomerados, para que estas industrias aprovechen los envases de Tetra Pak posconsumo y posindustria como materia prima. De esta forma, estas empresas fabrican papel, cajas corrugadas, cartón gris, tubos de cartón, muebles, láminas aglomeradas y tejas. En Colombia, existen tres plantas de reciclaje de pulpa de papel, que incluyen el reciclaje de los envases de Tetra Pak, ubicadas en las ciudades de Bogotá, Cali y Medellín (planta integrada). Por otro lado, existen dos plantas que aprovechan los residuos de polietileno y aluminio provenientes del despulpado de los envases de Tetra Pak, una en Bogotá y una en Medellín.

      .tarjeta.color-7.p-4(titulo="Pasos claves")
        h4 Pasos claves
        .row.align-items-center
          .col-lg-2
            figure
              img(src='@/assets/curso/tema2/icon.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p Es importante que las fuentes de material de las bodegas, principalmente las de origen doméstico, comercial e institucional, que consumen los envases de Tetra Pak, realicen tres sencillos pasos antes de desecharlos en el contenedor de residuos reciclables: Enjuagar, escurrir y aplanar. Únicamente cuando algún operador o bodega maneje material posindustrial que ha tenido contacto con productos (leches y jugos) en algún cliente industrial (por ejemplo, Colanta, Alpina, Incolacteos, Parmalat, Postobón, etc.), es necesario lavarlo con abundante agua, debido al alto contenido de líquido. No es necesario separar los envases por tipo, esto quiere decir que se pueden mezclar envases de Tetra Pak de leche, jugos y licores sin problema.

    p.mb-4 En el siguiente recurso se muestran algunos requerimientos y necesidades del proceso de reciclaje del Tetra Pak. Se recomienda tomar nota atenta de los aspectos más importantes. ¡Adelante!

    h4.text-center Reciclaje del Tetra Pak

    TabsC.color-acento-contenido.mb-4
      .py-3.py-md-0(titulo="Máquinas compactadoras")
        .row.color-8.p-4.align-items-center
          .col-lg-8
            h4 Máquinas compactadoras
            p Si la bodega cuenta con máquina compactadora, siga las siguientes recomendaciones:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 Enfardar el material en compactadoras hidráulicas
              li 
                i.fas.fa-check
                p.mb-2 Si se tiene montacargas, se pueden armar pacas o fardos de máximo 300 kg. Sin embargo, el peso ideal está entre 100 y 150 kg por paca.
              li 
                i.fas.fa-check
                p.mb-2 Si no se tiene montacargas, se deben armar pacas de máximo 50 kg.
              li 
                i.fas.fa-check
                p.mb-2 Armar la paca únicamente con envases posconsumo de Tetra Pak
              li 
                i.fas.fa-check
                p.mb-2 Verificar que el material esté lo más seco posible, sin contenido de producto o agua.
              li 
                i.fas.fa-check
                p.mb-2 Siempre entregar compactado y nunca envolver las pacas en plástico.
              li 
                i.fas.fa-check
                p.mb-2 No envolver material posindustrial (material proveniente de rollos vencidos) en las pacas. Si hay material posindustrial, es necesario cortarlo a un tamaño máximo de 50 cm, para evitar problemas en el proceso de reciclaje.
              li 
                i.fas.fa-check
                p.mb-2 En el proceso de compactación, colocar cartón a cada lado de la paca para evitar que se desarme fácilmente.
              li 
                i.fas.fa-check
                p.mb-2 Amarrar la paca con alambre de calibre 12 y no con zuncho, porque se puede romper fácilmente.
              li 
                i.fas.fa-check
                p.mb-2 Después de armada la paca, fumigue con hipoclorito o cualquier inhibidor de malos olores y vectores.
          .col-lg-4
            figure
              img(src='@/assets/curso/tema2/img10.jpg', alt='Texto que describa la imagen')
      .py-3.py-md-0(titulo="En cuanto a reciclaje")
        .row.color-8.p-4.align-items-center
          .col-lg-8
            h4 En cuanto a reciclaje
            p Si la bodega cuenta con máquina compactadora, siga las siguientes recomendaciones:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 Cuando ya estén armadas las pacas, se debe designar un lugar dentro de la bodega para almacenarlas.
              li 
                i.fas.fa-check
                p.mb-2 Este lugar debe ser seco y bajo techo, evitando que el material adquiera de nuevo humedad.
            p.mb-4 Armar la paca únicamente con envases posconsumo de Tetra Pak
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 Si tiene montacargas, puede apilar material en 4 niveles para ahorrar espacio.
              li 
                i.fas.fa-check
                p.mb-2 Si tiene montacargas, puede apilar material en 4 niveles para ahorrar espacio.
              li 
                i.fas.fa-check
                p.mb-2 Si no se tiene montacargas, se recomienda apilar en máximo 2 niveles dentro del espacio asignado para almacenar el material.
              li 
                i.fas.fa-check
                p.mb-2 Cuando no se cuente con compactadora hidráulica, se puede almacenar el material suelto, únicamente teniendo en cuenta que este debe ir en una lona o big bag (globo) separado de otros materiales.
          .col-lg-4
            figure
              img(src='@/assets/curso/tema2/img11.jpg', alt='Texto que describa la imagen')
      .py-3.py-md-0(titulo="Pasos claves")
        .row.color-8.p-4.align-items-center
          .col-lg-8
            h4 Pasos claves
            p Todas las plantas de reciclaje de envases de Tetra Pak reciben el material compactado o suelto. Para la recolección, tenga en cuenta:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 Comunicación previa con la planta de reciclaje.
              li 
                i.fas.fa-check
                p.mb-2 Tener en cuenta los horarios de recepción del material.
              li 
                i.fas.fa-check
                p.mb-2 Hay que tener en cuenta un máximo de un 15% de humedad por cada paca. 
              li 
                i.fas.fa-check
                p.mb-2 Comunicarse con la planta para tener en cuenta los documentos requeridos para el trámite de pagos.
          .col-lg-4
            figure
              img(src='@/assets/curso/tema2/img12.jpg', alt='Texto que describa la imagen')

    p.mb-4 <b>Estos son los requisitos que debe cumplir un residuo Tetra Pak para ser reciclado:</b>

    .tarjeta.color-6.p-4.mb-4
      .row
        .col-lg-1
          span
        .col-lg-10
          .row.align-items-center
            .col-lg-2
              figure
                img(src='@/assets/curso/tema2/3.png', alt='Texto que describa la imagen')
            .col-lg-10
             ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 No mezclar con otros envases de sólo plástico y aluminio, como los doypack o cajas plegadizas.
              li 
                i.fas.fa-check
                p.mb-2 Cualquier otro residuo diferente a los envases de Tetra Pak.
              li 
                i.fas.fa-check
                p.mb-2 No mezclar con material posindustrial proveniente de rollos vencidos.
              li 
                i.fas.fa-check
                p.mb-2 Para que este material sea aceptado, los rollos deben ser cortados a un tamaño máximo de 50 cm X 50 cm antes de ser compactados y entregados a planta.
        .col-lg-1
          span
    p.mb-4 La mayor cantidad de envases que se encuentran en el mercado colombiano son Tetra Brik Aseptic (ladrillo) de todos los tamaños, los cuales contienen fibra marrón. 
    p.mb-4 Se pueden encontrar otro tipo de envases que contienen fibra blanca, pero su participación con respecto a los de fibra marrón es mínima. 

    .bg_grad-03
      .row.justify-content-center
        .col-lg-10.mb-4
          h5.mb-0 Figura 3 
          span Tipos de envases Tetra Pak 
        .col-lg-8
          figure
            img(src='@/assets/curso/tema2/img13.jpg', alt='Texto que describa la imagen')
      separador
    
      #t_2_4.titulo-segundo.color-acento-contenido(data-aos="fade")
        .h2 2.4 Vidrio

    p.mb-4 En Colombia, el mercado del reciclaje de vidrio inició en 1978, desde entonces la reinserción de este material a la cadena productiva ha disminuido el ingreso del mismo a rellenos sanitarios en el país. El vidrio es un material producto de la mezcla de algunos recursos naturales no tóxicos, como la arena, la caliza, la soda y el feldespato. Estos materiales permiten que su ciclo de vida sea perfecto. En el reciclaje está el comienzo y el final de cada envase de vidrio.

    .row.align-items-center.mb-4
      .col-lg-6
        .tarjeta.color-1.p-5
          h4 Sostenibilidad
          p.mb-0 El vidrio es un producto que cumple con el marco de la sostenibilidad ambiental, porque puede ser reciclado varias veces, debido a que su calidad, pureza y transparencia lo permite, minimizando los impactos ambientales negativos en los rellenos sanitarios; además, genera beneficios sociales, porque se generan ingresos directos e indirectos, y es económicamente viable, porque los materiales se regresan al ciclo productivo y no se utiliza tanta materia prima.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img14.jpg', alt='Texto que describa la imagen')
    
    p.mb-2 <b>Luego del consumo inicial</b>
    p.mb-4 Además de esto, el vidrio posconsumo se convierte en el componente más importante en la fabricación de nuevas botellas, lo que permite un ahorro significativo de energía: 1 kg de vidrio reciclado ahorra la energía equivalente a 25 minutos de un computador encendido y cada tonelada de vidrio reciclado evita el consumo de 1.2 toneladas de materia prima virgen y previene la emisión de más de media tonelada de gases de efecto invernadero. El término casco se utiliza a nivel industrial para denominar al vidrio posconsumo.
    p.mb-2 <b>Cadena del vidrio</b>
    p.mb-4 Esta es la cadena básica del vidrio.

    .bg_grad-04
      .row.justify-content-center.mb-4
        .col-lg-10.mb-4
          h5.mb-0 Figura 4
          span Cadena del vidrio
        .col-lg-10
          figure
            img(src='@/assets/curso/tema2/img15.jpg', alt='Texto que describa la imagen')
          figcaption Nota. ANDI (2017) Calidades de materiales para reciclaje. p.7
      p.mb-4 La calidad del material que se encuentra discriminado para la compra es: material sucio y material limpio. Para que el proveedor pueda garantizar la calidad del material, es necesario contar con una preparación previa, la cual se describe a continuación:

      .row.mb-5
        .col-md-6.col-lg.mb-5.mb-lg-0
          .tarjeta-avatar
            img(src='@/assets/curso/tema2/avtr1.svg' alt='AvatarTop')
            .tarjeta.color-9
              .p-4
                h4.text-center Separar
                p Se trata de clasificar por colores blanco, ámbar, verde, y, a su vez, clasificarlos por limpio y sucio. Quitar tapas, anillos y demás elementos ajenos al material, catalogados como contaminantes del vidrio.

        .col-md-6.col-lg.mb-5.mb-lg-0
          .tarjeta-avatar
            img(src='@/assets/curso/tema2/avtr2.svg' alt='AvatarTop')
            .tarjeta.color-9
              .p-4
                h4.text-center Quebrar
                p Esta es una recomendación al proveedor, más no es una condición para la venta del material, es decir que el vidrio puede entregarse completo; sin embargo, se recomienda al proveedor efectuar la rotura, puesto que disminuye volumen en el transporte.

        .col-md-6.col-lg.mb-5.mb-lg-0
          .tarjeta-avatar
            img(src='@/assets/curso/tema2/avtr3.svg' alt='AvatarTop')
            .tarjeta.color-9
              .p-4
                h4.text-center Almacenar
                p Durante el almacenamiento, no mezclar las calidades de limpio y sucio, ni los diferentes tipos de colores. 

    p.mb-2 <b>Tipos de vidrio</b>
    p.mb-4 Analice la siguiente tabla en la que se presentan los tipos de vidrio.

    .row.justify-content-center.mb-4
      .col-lg-10.mb-4
        h5.mb-0 Tabla 4 
        span.mb-2 Tipos de vidrio 
        .tabla-a.color-acento-botones 
          table
            caption Nota. Guía para elaboración y presentación del plan de gestión integral de residuos hospitalarios y similares-pgirhs aplicado a microgeneradores. Área Metropolitana de Bucaramanga (2002). 
            thead
              tr(style='background-color: #80CAB6')
                <th colspan="3">CARACTERIZACIÓN CUANTITATIVA</th>
            tbody
              tr(style='background-color: #AADFD1')
                td TIPO DE VIDRIO POSCONSUMO COMERCIALIZABLE
                td DESCRIPCIÓN
                td CONTAMINANTES DEL PROCESO
              tr
                td(style='background-color: #D3EDE5') Vidrio envase ámbar
                td(style='background-color: #D3EDE5') Se compra completo o roto. No debe mezclarse con otros colores ni con vidrio plano. El vidrio de refractarias o cafeteras no es reciclable, por tanto, no debe mezclarse con ningún tipo de vidrio posconsumo para venta.
                <td rowspan="6" style='background-color: #F3FEFB' > Material ferroso (magnético): puntillas, tapas, clavos, varillas, limadura de hierro, alambre o cualquier elemento magnético. Material no ferroso (no magnético): principalmente el aluminio, en cualquier presentación, cobre, zinc, estaño, plomo.Vidrios especiales: espejos, vidrio laminado (automóviles), bombillos, fardas, tubos fluorescentes, vidrio de ampolletas.Material inorgánico: piedras de cualquier tipo, gravilla, arena, cemento, concreto, cerámica, vidrio refractario o de refractarias Materiales orgánicos: trapos, papel, cartón, madera, plástico (bolsas, pitillos), caucho, tierra, jeringas.</td>
              tr(style='background-color: #F6F6F6')
                td Vidrio envase verde
                td Se compra completo o roto. No debe mezclarse con otros colores ni con vidrio plano.
              tr(style='background-color: #D3EDE5')
                td Vidrio envase transparente (blanco)
                td Se compra completo o roto. No debe mezclarse con otros colores ni con vidrio plano.
              tr(style='background-color: #F6F6F6')
                td Vidrio plano transparente
                td Se compra completo o roto. No debe mezclarse con otros colores ni con envases. El espejo no es reciclable, por tanto, no debe mezclarse con ningún tipo de vidrio posconsumo para venta.
              tr(style='background-color: #D3EDE5')
                td Vidrio plano bronce
                td Se compra completo o roto. No debe mezclarse con otros colores ni con envases. El espejo no es reciclable, por tanto, no debe mezclarse con ningún tipo de vidrio posconsumo para venta.
    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-12
              .row.mb-2
                .col-lg-1
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-11
                  p.mb-4 Para profundizar en factores alusivos al vidrio y sus procesos de reciclaje, observe con atención los videos que se le proponen a continuación:
                  .row
                    .col-lg-6
                      a.anexo.mb-3(href="https://www.youtube.com/watch?v=QnvrGBHh2XE" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-link.svg")
                        .anexo__texto
                          p <b>Enlace web.</b>> Socyaoficial (2015, 25 agosto) Te invitamos a conocer cómo funciona la plata de reciclaje de vidrio.
                    .col-lg-6
                      a.anexo.mb-3(href="https://www.youtube.com/watch?v=rGAKfGJqheg" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-link.svg")
                        .anexo__texto
                          p <b>Enlace web.</b>> Telemadrid (2011, 30 agosto) Así se recicla el vidrio.
    separador

    #t_2_5.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.5 Metal

    .bloque-texto-g.color-acento-contenido.p-4.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img16.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 El acero y la chatarra ferrosa son infinitamente reutilizables en la naturaleza, aunque se tienen unas mermas en su procesamiento. La producción de acero a partir del reciclaje de chatarra ferrosa es amigable y sostenible con el medio ambiente, porque disminuye el consumo de recursos naturales no renovables. El acero producido a partir del reciclaje y fundición de chatarra ferrosa queda en condición de acero nuevo cumpliendo con todas las características físico-mecánicas exigidas en las normas nacionales e internacionales para la fabricación de acero.
    p.mb-4 La mayoría de siderúrgicas colombianas son semiintegradas, lo que implica que su materia prima es la chatarra ferrosa. La chatarra ferrosa se puede procesar, manipular, preparar y fundir, siempre y cuando no presente un riesgo para la salud de las personas, el medio ambiente o riesgo para los bienes e instalaciones.

    .bg_grad-05
      .row.justify-content-center.mb-5
        .col-lg-10.mb-4
          h5.mb-0 Figura 5
          span  Círculo del reciclaje del metal
        .col-lg-10
          figure
            img(src='@/assets/curso/tema2/img17.jpg', alt='Texto que describa la imagen')
          figcaption Nota. ANDI (2017). Calidades de materiales para reciclaje. p.27
      p.mb-5 Conozca, en el siguiente recurso, los requisitos que exige el proceso de reciclaje del metal.

      .tarjeta.colorsly.p-4
        SlyderA(tipo="b")
          .row
            .col-md-6.mb-4.mb-md-0
              h4 Requisitos que debe cumplir un residuo de metal para ser reciclado
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  p.mb-0 Recipientes cerrados y presurizados – Cilindros con válvulas, sistemas de refrigeración sin purgar.
                li 
                  i.fas.fa-check
                  p.mb-0 Residuos peligrosos (sólidos, líquidos y plasma).
                li 
                  i.fas.fa-check
                  p.mb-0 Canecas de pintura con residuo superior al 10 %.
                li 
                  i.fas.fa-check
                  p.mb-0 Pilas y baterías.
                li 
                  i.fas.fa-check
                  p.mb-0 Cofres o cajas fuertes rellenos de concreto.
                li 
                  i.fas.fa-check
                  p.mb-0 Filtros de aceite contaminados con aceite.
                li 
                  i.fas.fa-check
                  p.mb-0 Productos electrónicos.
            .col-md-6
              figure
                img(src='@/assets/curso/tema2/4.png', alt='Texto que describa la imagen')

          .row
            .col-md-6.mb-4.mb-md-0
              h4 Requisitos que debe cumplir un residuo de metal para ser reciclado
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  p.mb-2 Metales pesados (plomo, cadmio, etc.).
                li 
                  i.fas.fa-check
                  p.mb-0 Amortiguadores sellados y similares.
                li 
                  i.fas.fa-check
                  p.mb-0 Transformadores y capacitores con askarel.
                li 
                  i.fas.fa-check
                  p.mb-0 Dispositivos con contenido de mercurio.
                li 
                  i.fas.fa-check
                  p.mb-0 Materiales con radiactividad.
                li 
                  i.fas.fa-check
                  p.mb-0 Acero inoxidable.
                li 
                  i.fas.fa-check
                  p.mb-0 Rotores de motores eléctricos y que contengan cobre.
                li 
                  i.fas.fa-check
                  p.mb-0 Cemento, tierra, concreto, ladrillos y otros similares.
                li 
                  i.fas.fa-check
                  p.mb-0 Chatarra con elementos químicos.
            .col-md-6
              figure
                img(src='@/assets/curso/tema2/5.png', alt='Texto que describa la imagen')
          
          .row
            .col-md-6.mb-4.mb-md-0
              h4 Requisitos que debe cumplir un residuo de metal para ser reciclado
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  p.mb-2 Piezas y partes con asbesto.
                li 
                  i.fas.fa-check
                  p.mb-0 Chatarra con gomas, cauchos, asfalto y otros polímeros.
                li 
                  i.fas.fa-check
                  p.mb-0 Calamina, cascarilla y otros derivados de oxidaciones e impurezas y degradaciones del acero.
                li 
                  i.fas.fa-check
                  p.mb-0 Residuales de los procesos de corte y soldadura.
                li 
                  i.fas.fa-check
                  p.mb-0 Cuerpos moledores de la industria cementera y cerámica, con alto contenido de cromo y manganeso.
                li 
                  i.fas.fa-check
                  p.mb-0 Aleaciones de aceros de alta resistencia, como brocas con tungsteno, cromo-vanadio.
                li 
                  i.fas.fa-check
                  p.mb-0 Otros considerados peligrosos o no aptos.
            .col-md-6
              figure
                img(src='@/assets/curso/tema2/6.png', alt='Texto que describa la imagen')
    p.mb-4 Hay que mencionar, además, que existen condiciones preestablecidas, bajo las cuales serán, o no, aceptados algunos materiales. Se podrá recibir chatarra derivada de los siguientes orígenes o condiciones, si cumplen los requisitos descritos a continuación:

    .row.align-items-center.mb-2
      .col-lg-6
        LineaTiempoD
          .row.align-items-center(numero="1" titulo="Material ferroviario, rieles y tapas de alcantarilla:")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img18.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 El proveedor siempre debe certificar su origen legal y el comprador responsable informará al patio su envío.

          .row.align-items-center(numero="2" titulo="Tanques de almacenamiento de combustible:")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img19.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 Se reciben mediante la presentación de un certificado de desgasificación y tener dos aberturas de un mínimo de 200 x 200 mm.

          .row.align-items-center(numero="3" titulo="Material de guerra, bélico, morteros, balas y similares:")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img20.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 Se recibe mediante la presentación de declaración escrita de organismo militar competente informando que la chatarra se encuentra completamente desactivada y no presenta peligro, pudiendo ser manejada, cizallada, prensada o fundida.

          .row.align-items-center(numero="4" titulo="Tubería petrolera de cañoneo")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img21.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 La tubería petrolera de cañoneo debe venir sin los estopines y sin el ducto interior donde vienen las cargas explosivas.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img22.jpg', alt='Texto que describa la imagen')

    .row.align-items-center.mb-4
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img23.jpg', alt='Texto que describa la imagen')
      .col-lg-6
        LineaTiempoD
          .row.align-items-center(numero="5" titulo="Cilindros de gases")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img24.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 Sólo serán aceptados si estuviesen despresurizados y sin válvulas.

          .row.align-items-center(numero="6" titulo="Canecas posconsumo agroquímico:")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img25.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 Sólo serán aceptadas si presentan certificado de triple lavado, entregado por la empresa, firmado por químico o agroquímico, siempre que presenten símbolos de “peligro”, “riesgo de envenenamiento” y otros similares.

          .row.align-items-center(numero="7" titulo="Material con riesgo biológico:")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img26.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 Para material derivado de residuos biológicos u hospitalarios, como jeringas, instrumentación, etc, se debe tener certificado que ya fueron tratados y el riesgo fue eliminado para proceder con la fundición.

          .row.align-items-center(numero="8" titulo="Material que requiere operación específica")
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/img27.jpg', alt='Texto que describa la imagen')
            .col-md-8
              p.mb-0 Materiales de difícil descargue, extradimensionados o cuyo peso sea superior a 4 toneladas deberán ser comunicados con anticipación, para coordinar, o no, su recepción.

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-12
              .row.mb-0
                .col-lg-1
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-11
                  p.mb-4 Diríjase al Anexo_3_Tabla5_TiposDeMetales, y afiance su saber sobre el proceso de aprovechamiento y tratamiento de los residuos (metal). Asimismo, observe atentamente el video que se encuentra en el siguiente enlace:
                  .row
                    .col-lg-6
                      a.anexo.mb-0(href="https://www.youtube.com/watch?v=QnvrGBHh2XE" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-link.svg")
                        .anexo__texto
                          p <b>Enlace web.</b>> Tecmany Domotica (2013, 7 julio) Reciclaje de metales
    separador 

    #t_2_6.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.6 Residuos de construcción y demolición (RCD)

    .row.align-items-center 
      .col-lg-6
        .tarjeta.color-1.px-5.py-5
          br
          p.mb-0 Los sobrantes de las actividades de demolición, excavación, construcción y/o reparaciones de las obras civiles, o de otras actividades conexas, complementarias o análogas, son conocidos como los RCD. Los residuos de construcción y demolición son materiales con un alto potencial de ser reciclados, debido a la composición de sus materiales. En aquellos lugares donde no se realizan separaciones de RCD, se desaprovechan materias primas, que, con un adecuado tratamiento, podrían ser recicladas o reutilizadas.
          br
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img28.jpg', alt='Texto que describa la imagen')

    p.mb-4 Por otro lado, el no aprovechamiento de estos residuos causa problemáticas ambientales, como la inadecuada disposición, la reducción de la vida útil de rellenos sanitarios y sitios de disposición final de RCD, e impactos negativos, como el cambio paisajístico, la contaminación de fuentes hídricas, la generación de material particulado, la compactación y cambio de uso de los suelos, la colmatación de los sistemas de captación de aguas lluvia, entre otros.

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-12
              .row.mb-0
                .col-lg-1
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-11
                  p.mb-4 Diríjase al Anexo_3_Tabla5_TiposDeMetales, y afiance su saber sobre el proceso de aprovechamiento y tratamiento de los residuos (metal). Asimismo, observe atentamente el video que se encuentra en el siguiente enlace:
                  .row
                    .col-lg-6
                      a.anexo.mb-0(href="https://www.youtube.com/watch?v=QnvrGBHh2XE" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-pdf.svg")
                        .anexo__texto
                          p <b>Anexo.</b>> 4_Tabla6_ClasificaciónRCD
    p.mb-4 Habría que decir también que los diferentes residuos que se originan en la construcción y demolición de obras pueden ser aprovechados y otros no, por lo que sólo pueden ser llevados a un sitio de disposición final. A continuación, se muestran las alternativas de uso:

    .bg_grad-06
      .row.justify-content-center.mb-4
        .col-lg-10.mb-2
          h5.mb-0 Tabla 7
          span.mb-2 Alternativas de gestión de uso de los residuos
        .col-lg-8
          .tabla-a.color-acento-botones 
            table
              thead
                tr(style='background-color: #80CAB6')
                  th Residuo
                  th Alternativa de uso
              tbody
                tr(style='background-color: #ECF7F4')
                  td.text-center Concretos
                  td 
                    p.mb-0 Reutilizar como masa para rellenos
                    p.mb-0 Reutilizar como suelos en carreteras
                    p.mb-0 Reciclar como grava suelta
                    p.mb-0 Reciclar para producción de morteros y cemento
                    p.mb-0 Reciclar como granulado
                tr(style='background-color: #D3EDE5')
                  td.text-center Cerámicos
                  td
                    p.mb-0 Reciclar como adoquín
                    p.mb-0 Reciclar como fachadas
                    p.mb-0 Reciclar para acabados
                tr(style='background-color: #ECF7F4')
                  td.text-center Asfalto
                  td 
                    p.mb-0 Reutilizar como masa para rellenos
                    p.mb-0 Reciclar como asfalto
                tr(style='background-color: #D3EDE5')
                  td.text-center Metales
                  td 
                    p.mb-0 Reutilizar para aplicación en otros productos
                    p.mb-0 Reciclar como aleación
                tr(style='background-color: #F6F6F6')
                  td.text-center Madera
                  td 
                    p.mb-0 Reutilizar para casetones, vallados y linderos
                    p.mb-0 Reciclar para tableros y aglomerados
                tr(style='background-color: #D3EDE5')
                  td.text-center Vidrio
                  td 
                    p.mb-0 Reciclaje para vidrio
                tr(style='background-color: #D3EDE5')
                  td.text-center Pétreos
                  td
                    p.mb-0 Reutilizar como áridos finos y gruesos
                tr(style='background-color: #ECF7F4')
                  td.text-center Plásticos
                  td 
                    p.mb-0 Reciclar como plásticos
                tr(style='background-color: #D3EDE5')
                  td.text-center Tejas, bloques, entre otros
                  td 
                    p.mb-0 Reciclar como base para nuevos productos
                tr(style='background-color: #F6F6F6')
                  td.text-center Tierra de excavación
                  td 
                    p.mb-0 Reutilizar como relleno y recuperación de salud
                    p.mb-0 Estabilización de suelos
                tr(style='background-color: #D3EDE5')
                  td.text-center Elementos arquitectónicos
                  td 
                    p.mb-0 Reutilizar como nuevos productos 
      .row.justify-content-center.mb-4
        .col-lg-10
          .tarjeta.color-4.p-4
            .row.align-items-center 
              .col-lg-12
                .row.mb-0
                  .col-lg-1
                    figure.mb-2
                      img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                  .col-lg-11
                    p.mb-4 Visualice estos dos videos para ampliar su saber respecto del reciclaje de desechos de construcción:
                    .row
                      .col-lg-6
                        a.anexo.mb-0(href="https://www.youtube.com/watch?v=kmY7FGBXzEU" target="_blank")
                          .anexo__icono
                            img(src="@/assets/template/icono-link.svg")
                          .anexo__texto
                            p <b>Enlace web.</b>> Unoreciclaje (2017 13 septiembre). Planta reciclaje para residuos de madera, RCD y RSI
                      .col-lg-6
                        a.anexo.mb-0(href="https://www.youtube.com/watch?v=Y0wYrrdN48Q" target="_blank")
                          .anexo__icono
                            img(src="@/assets/template/icono-link.svg")
                          .anexo__texto
                            p <b>Enlace web.</b>> Noticias Caracol (2019, 15 marzo). ¿Cómo se hace el reciclaje de desechos de construcción y llantas?
      separador

    #t_2_7.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.7 Residuos aparatos eléctricos, electrónicos y de telecomunicaciones (RAEE)

    p.mb-4 Los RAEE son residuos de manejo diferenciado y se prohíbe su disposición final en rellenos sanitarios. Deben ser recolectados y gestionados por los productores y se prioriza su aprovechamiento mediante empresas gestoras que cuenten con licencia ambiental para ello. Es decir, la normativa busca incentivar el aprovechamiento de los residuos de aparatos eléctricos y electrónicos desde una perspectiva económica y social, y promover la participación e integración de todos los actores involucrados en la elaboración de las estrategias, planes y proyectos que desarrollen la gestión integral de los RAEE, entre otros aspectos.

    TabsA.color-acento-contenido.mb-4
      .tarjeta.color-10.p-4(titulo="Categorías de los RAEE")
        h4 Categorías de los RAEE
        .row.align-items-center
          .col-lg-2            
            figure
              img(src='@/assets/curso/tema2/icon2.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p.mb-0 Los grandes y pequeños electrodomésticos abarcan la línea blanca, mientras los equipos de informática y telecomunicaciones conforman la línea gris; y los aparatos electrónicos de consumo hacen parte de la línea marrón.

      .tarjeta.color-10.p-4(titulo="Categorías alternas")
        h4 Categorías alternas
        .row.align-items-center
          .col-lg-2            
            figure
              img(src='@/assets/curso/tema2/icon2.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p.mb-0 Las demás categorías corresponden a los otros tipos de aparatos eléctricos y electrónicos que pueden ser usados tanto en el hogar como en las empresas, el comercio o en las instituciones, como los aparatos de alumbrado, las herramientas eléctricas y electrónicas (con excepción de las herramientas industriales fijas de gran envergadura), los juguetes o equipos deportivos y de ocio, los aparatos médicos (con excepción de todos los productos implantados e infectados), los instrumentos de vigilancia y control y las máquinas expendedoras de productos y dinero.

      .tarjeta.color-10.p-4(titulo="Sustancias peligrosas")
        h4 Sustancias peligrosas
        .row.align-items-center
          .col-lg-2            
            figure
              img(src='@/assets/curso/tema2/icon2.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p.mb-0 Asimismo, se han identificado las sustancias peligrosas que más comúnmente están presentes en los RAEE. Hay que tener en cuenta que los RAEE pueden o no ser peligrosos; si el RAEE es no peligroso, se debe considerar si es especial o reciclable o no aprovechable; y si es peligroso, la forma de saberlo es teniendo en cuenta su composición, como en la tabla siguiente.

      .tarjeta.color-10.p-4(titulo="Categorías alternas")
        h4 Según la ley
        .row.align-items-center
          .col-lg-2            
            figure
              img(src='@/assets/curso/tema2/icon2.svg', alt='Texto que describa la imagen')
          .col-lg-10
            p.mb-0 La Ley 1672 de 2013 le da el carácter de manejo diferenciado a los RAEE, prohíbe su disposición final en los rellenos sanitarios y los restringe a rellenos de seguridad, para que sean retomados por los productores de aparatos eléctricos y electrónicos, mediante sistemas de recolección y de gestión ambientalmente segura. Así, se busca que el consumidor devuelva los RAEE sin ningún costo.

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-12
              .row.mb-0
                .col-lg-1
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-11
                  p.mb-2 Con el fin de profundizar y asimilar todos los aspectos relativos a los residuos RAEE, visite el Anexo_5_Tabla10_SustanciasPeligrosasRAEE
                  p.mb-4 Asimismo, observe responsablemente los videos que se proponen en los siguientes enlaces: 
                  .row
                    .col-lg-6
                      a.anexo.mb-0(href="https://www.youtube.com/watch?v=5upwOp_73yw" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-link.svg")
                        .anexo__texto
                          p <b>Enlace web.</b>> Unoreciclaje (2015, 5 noviembre). Planta de reciclado de R.A.E.E
                    .col-lg-6
                      a.anexo.mb-0(href="https://www.youtube.com/watch?v=PwJgk1uAzxA" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-link.svg")
                        .anexo__texto
                          p <b>Enlace web.</b>> Twenergy (2015, 26 de marzo). El reciclaje de materiales electrónicos
    separador

    #t_2_8.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.8 Residuos orgánicos

    .row.align-items-center.mb-4
      .col-lg-6
        .tarjeta.color-1.px-5.py-5
          br
          p.mb-0 La mayor cantidad de residuos sólidos que se generan son orgánicos, por lo que esto representa una problemática por resolver. De acuerdo con la GTC 53-7 (2006), existen diferentes estrategias alternativas de tratamiento de residuos orgánicos no peligrosos, las cuales consisten principalmente en la aplicación de procesos biológicos y/o bioquímicos, termoquímicos, físicos y/o fisicoquímicos.
          br
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img29.jpg', alt='Texto que describa la imagen')

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-4.p-4
          .row.align-items-center 
            .col-lg-12
              .row.mb-0
                .col-lg-1
                  figure.mb-2
                    img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
                .col-lg-11
                  p.mb-4 Para estudiar todos los aspectos teóricos y conceptuales relativos al manejo y administración de residuos sólidos orgánicos, diríjase al Anexo_6_ResiduosOrganicosMetodosAprovechamiento
                  .row
                    .col-lg-8
                      a.anexo.mb-0(href="https://www.youtube.com/watch?v=5upwOp_73yw" target="_blank")
                        .anexo__icono
                          img(src="@/assets/template/icono-pdf.svg")
                        .anexo__texto
                          p <b>Anexo.</b>> Anexo_6_ResiduosOrganicosMetodosAprovechamiento
                
</template>

<script>
export default {
  name: 'Tema2',
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

<style lang="sass"></style>
