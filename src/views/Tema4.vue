<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Aprovechamiento y tratamiento residuos peligrosos

    p.mb-4 El personal que labora en las empresas de aprovechamiento y tratamiento de residuos está propenso a varios riesgos, por ende, es importante el uso de elementos de protección personal y seguridad y salud en los ambientes de trabajo.

    .row.justify-content-center.mb-4
      .col-lg-10.mb-2
        h5.mb-0 Tabla 15
        span.mb-2 Riesgos en la labor
      .col-lg-8
        .tabla-a.color-acento-botones.mb-2
          table
            thead
              tr(style='background-color: #80CAB6')
                th Riesgos
                th Observaciones
            tbody(style='background-color: #ECF7F4')
              tr
                td.text-center <b>Físico ruido</b>>
                td Ruido de equipos y maquinaria en general en la planta de reciclaje, como es el caso de romper el vidrio, triturar algún material.
                  p Se requiere de protección acústica.
              tr
                td.text-center <b>Biológico</b>>
                td Mordedura de algún animal, como los roedores, porque, en algunos casos, el almacenamiento de materiales, como envases, llega con residuos que atraen estos vectores.
                  p Se requiere manejo de plagas en el lugar y estar vacunado contra la hepatitis b.
              tr
                td.text-center <b>De seguridad mecánico</b>>
                td Aplastamiento o corte de alguna extremidad, como las manos, con herramientas o maquinaria.
                  p Protección, demarcación de áreas, uso de casco, nivel de apilado requerido según norma, amarras de la mercancía, sensores de movimiento en la maquinaria, capacitación al personal de la labor, guantes de carnaza, overol y no uso de joyas o accesorios que puedan crear atrapamientos en la maquinaria.
              tr
                td.text-center <b>Físico  iluminación</b>>
                td Por exceso al aire libre o por defecto. Si es por exceso, uso de monogafas con filtro solar; y si es por defecto, mejor iluminación del lugar.
              tr
                td.text-center <b>Físico vibración</b>
                td La vibración de la maquinaria. El operario tiene que entrar en contacto físico con la máquina, razón por la cual sufre mayor exposición a vibración en cuerpo total. Uso de elementos que mitiguen la vibración. 
              tr
                td.text-center <b>Biomecánico movimiento repetitivo</b>
                td Movimientos repetitivos en las actividades requieren pausas activas.
              tr
                td.text-center <b>Biomecánico sobreesfuerzo</b>
                td Manejo manual de cargas pesadas, uso de postura adecuada y control de peso
              tr
                td.text-center <b>Seguridad locativa</b>
                td Caída de objetos , caída a nivel de piso, uso de casco y botas
              tr
                td.text-center <b>Químicos</b>
                td Inhalación o contacto con la piel de sustancias químicas que se encuentren en los materiales. Se requiere de mascarilla de gases y guantes resistentes a químicos. 
        figcaption Nota. ANDI (2017) Calidades de materiales para reciclaje. p.7

</template>

<script>
export default {
  name: 'Tema4',
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
