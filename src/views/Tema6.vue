<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Transformadores de energía

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image':`url(${require('@/assets/curso/temas/t6/1.jpg')})`}")
      .bloque-texto-g__texto.p-4.py-lg-5
        br
        p.mb-5 La transformación de la energía es un proceso fundamental mediante el cual se convierten diversas fuentes energéticas en formas útiles para satisfacer las necesidades humanas. Este proceso abarca múltiples tecnologías, desde la generación eléctrica a partir de combustibles fósiles y energía nuclear, hasta el aprovechamiento de fuentes renovables como el agua, el sol o la biomasa.
        br
        br

    .row.bgc-2.align-items-center.p-2.p-md-3
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center
        
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-5 
              p En un contexto global orientado hacia la sostenibilidad, mejorar la eficiencia e impulsar la innovación en los procesos de transformación energética es clave para reducir el impacto ambiental y asegurar un suministro confiable de energía.
              p A continuación, se describen algunos de los principales procesos de transformación energética:
            .col-lg-3.d-none.d-lg-block
              img(src='@/assets/curso/temas/t6/2.png', alt='')  

          .row.justify-content-center.mb-5
            .col-lg-12
              AcordionA.mb-5(tipo="b" clase-tarjeta="bg-trans")
                .row(titulo="Refinación del petróleo")
                  .col-md-6.mb-3.mb-md-0
                    img(src='@/assets/curso/temas/t6/acord1.png', alt='')
                  .col-md-6.pe-lg-5
                    p La refinería transforma el petróleo crudo en productos derivados como gasolina, diésel, gas licuado, entre otros, para atender la demanda energética y productiva. Esta demanda varía con el tiempo, tanto en la cantidad total de derivados requeridos como en la proporción de cada uno, por lo que las refinerías deben adaptarse constantemente a estas condiciones del mercado.
                .row(titulo="Generación termoeléctrica")
                  .col-md-6.mb-3.mb-md-0
                    img(src='@/assets/curso/temas/t6/acord2.png', alt='')
                  .col-md-6.pe-lg-5
                    p En las centrales termoeléctricas, se utiliza energía térmica para convertir agua en vapor. Este vapor, una vez sobrecalentado, se dirige a una turbina, donde su energía cinética se convierte en energía mecánica; posteriormente, esta energía acciona un generador que produce electricidad. Las fuentes de energía primaria para este tipo de plantas suelen ser combustóleo o gas natural.
                .row(titulo="Generación nuclear")
                  .col-md-6.mb-3.mb-md-0
                    img(src='@/assets/curso/temas/t6/acord3.png', alt='')
                  .col-md-6.pe-lg-5
                    p La energía nuclear se genera a partir de reacciones de fisión (división de átomos pesados como el uranio) o fusión (unión de átomos ligeros). Estas reacciones liberan enormes cantidades de energía, que se utilizan para producir electricidad. La fisión con uranio es el método más común. La energía nuclear se considera una alternativa limpia y eficiente, ya que no emite gases contaminantes durante su operación; sin embargo, conlleva riesgos elevados debido a la radiactividad. Aunque la probabilidad de accidentes es baja, sus consecuencias pueden ser graves y duraderas.
                .row(titulo="Generación hidroeléctrica")
                  .col-md-6.mb-3.mb-md-0
                    img(src='@/assets/curso/temas/t6/acord4.png', alt='')
                  .col-md-6.pe-lg-5
                    p Las plantas hidroeléctricas convierten la energía potencial del agua en movimiento (energía hidráulica) en energía eléctrica. El agua fluye desde una altura y pasa por turbinas hidráulicas, que giran al ser impulsadas por el flujo, convirtiendo así la energía del agua en movimiento rotatorio. Esta energía se transmite a generadores que producen electricidad. La eficiencia de este proceso depende del volumen de agua y del desnivel (salto) disponible.
                .row(titulo="Generación geotermoeléctrica")
                  .col-md-6.mb-3.mb-md-0
                    img(src='@/assets/curso/temas/t6/acord5.png', alt='')
                  .col-md-6.pe-lg-5
                    p Las centrales geo termoeléctricas funcionan de manera similar a las termoeléctricas, pero la fuente de calor proviene del interior de la Tierra; se extrae una mezcla de agua y vapor desde el subsuelo a través de pozos geotérmicos. Esta mezcla se separa en un equipo especializado para obtener vapor seco, que luego se dirige a una turbina. Al igual que en otros sistemas, el vapor hace girar la turbina, generando electricidad mediante un generador.
                .row(titulo="Energía de la biomasa")
                  .col-md-6.mb-3.mb-md-0
                    img(src='@/assets/curso/temas/t6/acord6.png', alt='')
                  .col-md-6.pe-lg-5
                    p La biomasa puede transformarse en energía mediante procesos biológicos que descomponen materia orgánica en condiciones anaeróbicas (sin oxígeno). Entre los métodos más comunes se encuentran:
                    ul.lista-ul--color.sec2.fa-lista.mb-0
                      li
                        i.fas.fa-circle-check
                        span.mb-0 #[b Biometanización:] produce biogás, una mezcla de metano y dióxido de carbono, apto como combustible.
                      li
                        i.fas.fa-circle-check
                        span.mb-0 #[b Fermentación alcohólica:] permite obtener etanol, un biocombustible líquido.
                      li
                        i.fas.fa-circle-check
                        span.mb-0 #[b Despolimerización de materiales lignocelulósicos:] se logra mediante procesos químicos o enzimáticos para obtener lignina y azúcares simples, útiles como materia prima energética o para la industria.


</template>

<script>
export default {
  name: 'Tema6',
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
