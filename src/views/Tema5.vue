<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Economía circular

    p.mb-4 La economía circular es una estrategia innovadora de diseño, producción y creación de valor, que beneficia a las empresas, la sociedad y el medio ambiente, reemplazando el esquema clásico de producción de la “economía lineal”. En la “economía lineal”, se extraen recursos, se producen bienes, se consumen y al final se desechan. 

    .bloque-texto-g.color-acento-contenido.p-4.p-sm-4.p-md-5.mb-4 
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema5/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La economía circular, en cambio, busca optimizar el uso de insumos, incrementar la vida útil de los productos y, al final, por medio de la recirculación de materiales, no desperdiciar nada y reutilizarlo todo. Con esto, las empresas mitigan sus impactos ambientales, optimizan sus costos, generan nuevos ingresos e incrementan su rentabilidad.

    .row.justify-content-center.mb-4 
      .col-lg-10
        h5.mb-0 Figura 11
        span Economía lineal vs economía circular
        figure.mb-2
          img(src='@/assets/curso/tema5/fig1.jpg', alt='Texto que describa la imagen')

    p.mb-4 A continuación, profundice en algunos aspectos del orden operativo que refuerzan los principios de la economía circular.

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-8.p-4
          h4.text-center Las 9 R de la economía circular
          p.text-center Cuando se habla de economía circular, es muy probable que también se hable de las nueve erres de la misma. Las 9 R de la economía circular son niveles básicos a tener presentes.
          figure.mb-2
            img(src='@/assets/curso/tema5/fig.svg', alt='Texto que describa la imagen')

    p.mb-4 <b>Algunos ejemplos concretos de economía circular son:</b>

    .row.align-items-center.justify-content-center.mb-0
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/1.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Neumáticos viejos transformados en suelas de zapatos.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/2.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Ropa usada como material para fabricar aislantes térmicos en bioconstrucción.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/3.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Caucho desmenuzado para pavimento de parques infantiles.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/4.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Botellas de vidrio convertidas en aislante acústico, térmico y antihumedad, como el vidrio celular.
      
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/5.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Neumáticos viejos transformados en suelas de zapatos.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/6.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Ropa usada como material para fabricar aislantes térmicos en bioconstrucción.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/7.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Caucho desmenuzado para pavimento de parques infantiles.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/8.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Botellas de vidrio convertidas en aislante acústico, térmico y antihumedad, como el vidrio celular.
    
    .row.align-items-center.justify-content-center.mb-4
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/9.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Separadores de carriles bici de aparatos electrónicos.
      .col-lg-3.mb-4
        .tarjeta.color-11.py-2.px-0 
          .row.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema5/10.svg', alt='Texto que describa la imagen')
            .col-lg-8
              .row
                .col-lg-11
                  p.mb-0 Plástico usado para crear mobiliario urbano nuevo.

</template>

<script>
export default {
  name: 'Tema5',
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
