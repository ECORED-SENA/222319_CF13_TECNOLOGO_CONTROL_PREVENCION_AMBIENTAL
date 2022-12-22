<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Conceptos Generales 

    p.mb-4 Los sistemas de tratamiento y disposición de diferentes tipos de residuos suponen un conocimiento elemental de conceptos, términos e implementos que favorecen tal manejo.   

    figure.mb-4
      img(src='@/assets/curso/tema1/img1.jpg', alt='Texto que describa la imagen')

    p.mb-4 En el siguiente recurso didáctico, se mostrarán algunos de los más relevantes y de uso común, y que le favorecerán en el estudio de este componente formativo. 

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema1/icon.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Conceptos generales, tratamiento de residuos
                  p  Tabla1_CategoriaDeReciclajePapelCarton
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    

</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
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

<style lang="sass"></style>
