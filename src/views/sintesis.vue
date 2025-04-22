<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p Comprender los conceptos fundamentales de la electricidad es esencial para el aprendiz. En este componente conocerá las fuentes de energía, circuitos básicos y las magnitudes de medida, así como también la ley fundamental que las regula: la Ley de Ohm. Esto le permitirá adquirir los principios básicos necesarios para el diseño e instalación de circuitos eléctricos en construcciones domiciliarias.

    .row.justify-content-center
      .col-lg-12.mb-5.p-4
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Presenta los fundamentos de electricidad para instalaciones en casa, organizados en cuatro áreas clave: los principios básicos de la electricidad (características, tipos y energía eléctrica), las leyes fundamentales (Ohm, Kirchhoff, Joule y Watt), los elementos de un circuito eléctrico (resistencia, corriente y voltaje, con sus respectivas unidades de medida: ohmios, amperios y voltios), y la clasificación de la electricidad según su fuente, distinguiendo entre renovable y no renovable.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
