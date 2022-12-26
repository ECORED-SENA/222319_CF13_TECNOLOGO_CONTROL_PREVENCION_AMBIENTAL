<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Aprovechamiento y tratamiento residuos peligrosos

    p.mb-4 De acuerdo con el informe nacional de generación y manejo de residuos o desechos peligrosos Colombia 2014-2015 del Instituto de hidrología, meteorología y estudios ambientales (IDEAM) (2016), el aprovechamiento de los residuos peligrosos se entiende como toda actividad orientada a recuperar el valor remanente o el poder calorífico de los materiales que componen el residuo.

    .row.align-items-center.mb-4
      .col-lg-6
        .tarjeta.color-1.px-5.py-5
          p.mb-4 Las recomendaciones dadas por el Área Metropolitana del Valle de Aburrá (2011), en la guía para la gestión de residuos peligrosos, manifiestan que, para seleccionar el tipo de aprovechamiento adecuado, se debe realizar un estudio previo a cada residuo, teniendo en cuenta características químicas como la familia, el estado de la materia, la cantidad, la frecuencia de generación, el transporte del material, el valor del servicio, entre otros aspectos. De este modo, se puede tomar la decisión de si el residuo es susceptible de aprovechamiento o si definitivamente ya no tiene uso y ha llegado al fin de su ciclo de vida, momento en el cual deberá gestionarse su disposición final.
          p.mb-0 Existen diferentes técnicas de aprovechamiento para los residuos peligrosos y se clasifican de acuerdo al principio de desactivación de la peligrosidad.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema3/img1.jpg', alt='Texto que describa la imagen')
    separador

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.1 Tratamientos físicos

    p.mb-4 Consisten, principalmente, en la eliminación del contenido de agua del residuo sólido peligroso, con el fin de que esta no se filtre al suelo. Entre las diferentes técnicas, se encuentran:

    .row 
      .col-lg-3
        .tarjeta.color-9.p-4
          .row.justify-content-center
            .col-8
              figure.mb-4
                img(src='@/assets/curso/tema3/1.svg', alt='Texto que describa la imagen')
          h4.text-center Sedimentación
          p.text-center.mb-0 se asientan los sólidos por acción de la gravedad para separarlos del líquido.
      .col-lg-3
        .tarjeta.color-9.p-4
          .row.justify-content-center
            .col-8
              figure.mb-4
                img(src='@/assets/curso/tema3/2.svg', alt='Texto que describa la imagen')
          h4.text-center Centrifugación
          p.text-center.mb-0 se utiliza el movimiento circular para generar fuerza centrífuga que permite la remoción del agua.
      .col-lg-3
        .tarjeta.color-9.p-4
          .row.justify-content-center
            .col-8
              figure.mb-4
                img(src='@/assets/curso/tema3/3.svg', alt='Texto que describa la imagen')
          h4.text-center Autoclave
          p.text-center.mb-0 esta técnica, además de la evaporación del agua mediante calor y presión, esteriliza los residuos, minimizando su riesgo biológico.
      .col-lg-3
        .tarjeta.color-9.p-4
          .row.justify-content-center
            .col-8
              figure.mb-4
                img(src='@/assets/curso/tema3/4.svg', alt='Texto que describa la imagen')
          h4.text-center Absorción
          p.text-center.mb-0 es la adhesión de sustancias contaminantes gaseosas sobre superficies líquidas para que se disuelvan.
    separador

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.2 Tratamientos químicos

    p.mb-4 El principio de este tipo de tratamiento es la adición de un componente químico para la eliminación de la característica de peligrosidad del residuo. Entre las técnicas principales, se encuentran:

    SlyderF(columnas="col-lg-6 col-xl-4").mb-4
      .tarjeta-avatar
        img(src='@/assets/curso/tema3/avatar1.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center Oxidación y reducción química
            p adición de componentes ricos en oxígeno para la transformación de componentes peligrosos.

      .tarjeta-avatar
        img(src='@/assets/curso/tema3/avatar2.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center Neutralización
            p adición de sustancias ácidas o básicas, de acuerdo con las características de peligrosidad para la neutralización del pH.

      .tarjeta-avatar
        img(src='@/assets/curso/tema3/avatar3.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center Precipitación
            p uso de componentes químicos para la solidificación y posterior sedimentación de componentes peligrosos.

      .tarjeta-avatar
        img(src='@/assets/curso/tema3/avatar4.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center Decloración
            p eliminación química del cloro en los residuos.

      .tarjeta-avatar
        img(src='@/assets/curso/tema3/avatar5.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center Hidrólisis
            p ruptura de componentes peligrosos en soluciones acuosas, basándose en la adición de agua.

      .tarjeta-avatar
        img(src='@/assets/curso/tema3/avatar6.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center Electrólisis
            p ruptura de componentes peligrosos a partir de descargas eléctricas.
    separador

    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.3 Tratamientos fisicoquímicos

    p.mb-4 Este tipo de métodos emplea tanto sustancias químicas como procesos físicos para poder eliminar las características de peligrosidad en los residuos. Entre algunos métodos, se encuentran:

    .row.align-items-center.mb-4
      .col-lg-6
        AcordionA(tipo="a" clase-tarjeta="tarjeta colorgris")
          .row(titulo="Extracción de solventes")
            .col-lg-1
              span
            .col-md-11 
              p.mb-0 por el principio de polaridad, algunas sustancias que tienen características de peligrosidad se pueden migrar a fases acuosas o grasosas, para ser separadas posteriormente por decantación.

          .row(titulo="Floculación y coagulación")
            .col-lg-1
              span
            .col-md-11 
              p.mb-0 se agregan sustancias químicas con el fin de eliminar las cargas electrostáticas que tienen algunos componentes peligrosos; de este modo, se forman flocs que luego de una sedimentación se retiran de las fases acuosas.

          .row(titulo="Stripping")
            .col-lg-1
              span
            .col-md-11 
              p.mb-0 a través de corrientes de gas, se separan componentes de peligrosidad con características volátiles.

          .row(titulo="Lixiviación")
            .col-lg-1
              span
            .col-md-11 
              p.mb-0 se permite la separación de componentes líquidos solubles en su parte sólida.

          .row(titulo="Ozonólisis")
            .col-lg-1
              span
            .col-md-11 
              p.mb-0 fraccionamiento de moléculas peligrosas mediante el uso de ozono.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema3/img1.jpg', alt='Texto que describa la imagen')
    separador

    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.4 Tratamientos biológicos

    p.mb-4 En este tipo de tratamientos, se utilizan diferentes microorganismos, hongos, plantas y otros seres vivos en función de la reducción de peligrosidad de los residuos, para su posterior uso. Algunas de las técnicas más comunes son:

    .tarjeta.color-8.p-4.mb-4
      .row.align-items-center
        .col-lg-5
          figure
            img(src='@/assets/curso/tema3/img2.jpg', alt='Texto que describa la imagen')
        .col-lg-7
          ul.lista-ul--color
            li 
              i.fas.fa-check
              p.mb-2 <b>Lodos activados:</b> se realiza la biodegradación de especies orgánicas con lodo bioactivado en fase acuosa. 
            li 
              i.fas.fa-check
              p.mb-2 <b>Biológico giratorio:</b> un filtro rico en material bacteriano se pone en contacto con los residuos para eliminar las especies químicas orgánicas acuosas.
            li 
              i.fas.fa-check
              p.mb-2 <b>Lagunas aireadas:</b> en este tratamiento, se eliminan los componentes químicos peligrosos por oxidación en las cavidades profundas de la laguna.
            li 
              i.fas.fa-check
              p.mb-2 <b>Digestión anaerobia:</b> degradación de componentes a través de acción de microorganismos en ausencia de oxígeno.
            li 
              i.fas.fa-check
              p.mb-2 <b>Bioremediación:</b> eliminación de componentes peligrosos a través de mezclas de microorganismos y enzimas.
            li 
              i.fas.fa-check
              p.mb-2 <b>Landfarming:</b> los materiales contaminados son esparcidos en una superficie o en el suelo y, a través de métodos biológicos, se eliminan los contaminantes peligrosos de los residuos.
            li 
              i.fas.fa-check
              p.mb-2 <b>Fitorremediación:</b> a través de algunas especies vegetales, se extraen contaminantes inorgánicos de los suelos para acumularlos en el tejido vegetal.
    separador 

    #t_3_5.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.5 Técnicas de solidificación y encapsulamiento

    p.mb-4 Con este tipo de técnicas, se busca acumular, de forma inorgánica, los componentes de peligrosidad de los residuos. Entre las técnicas más utilizadas, se encuentran:

    .row
      .col-lg-10
        .row.align-items-center
          .col-lg-6
            SlyderF(columnas="col-12")
              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/tema3/5.svg' alt='AvatarTop')
                h4.text-center Solidificación:
                p.text-center a partir de los residuos tratados, se forma una masa monolítica, incrementando su dureza y disminuyendo la compresibilidad y permeabilidad.

              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
                h2.text-center Estabilización
                p.text-center a través de esta técnica, se busca reducir el área superficial de los RESPEL, para reducir la transferencia de masa y la solubilidad de los contaminantes.

              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
                h2.text-center Fijación inorgánica
                p.text-center los residuos sólidos peligrosos se mezclan con materiales como el cemento o la cal. 

              .tarjeta.color-acento-botones.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
                h2.text-center Encapsulamiento
                p.text-center los residuos sólidos peligrosos se insertan en capas de asfalto, polietileno, o vidrio.
          .col-lg-6 
            figure
              img(src='@/assets/curso/tema3/img3.jpg', alt='Texto que describa la imagen')
    separador

    #t_3_6.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.6 Técnicas térmicas

    p.mb-4 Las técnicas térmicas buscan la desintegración de los componentes peligrosos de los residuos sólidos a partir del incremento de temperatura; las más utilizadas en la industria son:

    .row.align-items-center.mb-4 
      .col-lg-6
        figure
          img(src='@/assets/curso/tema3/img4.jpg', alt='Texto que describa la imagen')
      .col-lg-6
        .tarjeta.color-8.p-4
          ul.lista-ul--color
            li 
              i.fas.fa-check
              p.mb-2 <b>Incineración:</b> combustión con oxígeno, donde se oxidan los componentes peligrosos del residuo sólido. 
            li 
              i.fas.fa-check
              p.mb-2 <b>Procesamiento en horno cementero: </b> se utiliza la misma unidad de producción de Clinker para la combustión de residuos.
            li 
              i.fas.fa-check
              p.mb-2 <b>Pirólisis:</b> descomposición térmica en ausencia de oxígeno.
            li 
              i.fas.fa-check
              p.mb-2 <b>Gasificación:</b> combustión incompleta en ausencia de oxígeno.
            li 
              i.fas.fa-check
              p.mb-2 <b>Arco de plasma:</b> volatilización y combustión del residuo por el contacto con gas energizado.
            li 
              i.fas.fa-check
              p.mb-2 <b>Oxidación en sal fundida: </b> oxidación sin llama, a temperaturas entre 1500 y 2000°C, donde los residuos están en contacto con sales alcalinas fundidas.
          
          

</template>

<script>
export default {
  name: 'Tema3',
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
