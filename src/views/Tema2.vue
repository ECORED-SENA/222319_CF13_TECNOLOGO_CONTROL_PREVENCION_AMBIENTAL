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
