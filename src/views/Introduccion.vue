<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .bg_grad-01
      p.mb-4 Para comenzar el estudio de este componente, explore el siguiente recurso:
      figure.mb-5
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
      .row.justify-content-center.mb-4
        .col-lg-10
          .tarjeta.colorintro.p-4 
            .row 
              .col-lg-1
                figure
                  img(src='@/assets/curso/temas/icon.png', alt='Texto que describa la imagen')
              .col-lg-11
                p.mb-4 Para adentrarse más y mejor en el estudio de este componente, considere sus respuestas a los anteriores interrogantes, a la vez que observa los videos que se proponen a continuación:
                .row 
                  .col-lg-6
                    a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=P9nY_4VIusE" target="_blank")
                      .anexo__icono
                        img(src="@/assets/template/icono-link.svg")
                      .anexo__texto
                        p <b>Enlace web.</b> Sonsón Televisión oficial. (2018). Inadecuada disposición de residuos sólidos [Video]. YouTube.
                      
                  .col-lg-6
                    a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=k8BouGzKtqA" target="_blank")
                      .anexo__icono
                        img(src="@/assets/template/icono-link.svg")
                      .anexo__texto
                        p <b>Enlace web.</b> Senado Colombia. (2017). Alerta sanitaria y ambiental en rellenos sanitarios del país [Video]. YouTube.

      p.mb-4 Para la elaboración de este componente, se abordaron varios autores conocidos en <b>manejo de residuos según normativa vigente,</b> de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos aquellos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de <b>prevención y control ambiental.</b>
      


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
