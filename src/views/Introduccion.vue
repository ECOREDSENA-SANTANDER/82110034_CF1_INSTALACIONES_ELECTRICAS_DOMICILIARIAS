<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.pb-0.pb-md-0.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p En este componente, se abordan los principios fundamentales de la electricidad que todo técnico en instalaciones eléctricas domiciliarias debe conocer. A través del estudio de conceptos clave como la corriente, el voltaje, la resistencia y la energía eléctrica, así como de leyes fundamentales como la de Ohm y las de Kirchhoff, se sientan las bases para el análisis, diseño e implementación de circuitos eléctricos. 

    p Además, se exploran los distintos tipos de corriente, componentes esenciales de un circuito, y la forma en que la energía se transforma y se distribuye en los sistemas eléctricos. Este conocimiento es esencial para garantizar instalaciones seguras, funcionales y eficientes en el ámbito residencial.

    .row.bgc-1.align-items-center.p-2.p-md-3(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center.mb-5
        
          .row.justify-content-center.align-items-center
            .col-lg-12
              figure
                .video
                  iframe(width="560" height="315" src="https://www.youtube.com/embed/vdPrCjWJSHo?si=X4NxENRo3LLXAua_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
              figcaption Video. 

</template>

<script>
export default {
  name: 'Introduccion',
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
