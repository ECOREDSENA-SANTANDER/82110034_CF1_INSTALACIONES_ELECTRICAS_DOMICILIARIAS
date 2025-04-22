<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Estudio de los divisores de tensión y corriente y del comportamiento dinámico de condensadores e inductores en circuitos eléctricos

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6(data-aos="fade-right")
        .subt.mb-4
          .row.align-items-center
            .col-md-auto.col-2
              img(src='@/assets/curso/temas/t7/subt.svg', alt='')
            .col-md-auto.col-10.ps-0
              h3.mb-0.text-white El divisor de tensión o divisor de voltaje
        p Es un principio fundamental en el análisis de circuitos eléctricos. Permite calcular el voltaje que cae sobre una o varias resistencias conectadas en serie, a partir del voltaje total aplicado al circuito.
        p Este método se aplica directamente cuando se trabaja con dos resistencias en serie. Si el circuito contiene más de dos resistencias, se debe aplicar el divisor de voltaje de forma progresiva, agrupando resistencias de dos en dos y resolviendo paso a paso hasta alcanzar la resistencia de interés.
        .tarjeta.bg4.p-4.px-lg-5
          h5.mb-0 El divisor de voltaje es especialmente útil cuando no se dispone del valor de la corriente eléctrica en el circuito, pero sí se conocen los valores de las resistencias. En estos casos, no es posible aplicar directamente la Ley de Ohm, por lo que el divisor de tensión se convierte en una herramienta clave para determinar los voltajes parciales en cada componente.
      .col-lg-6(data-aos="fade-left")
        .bg-grad1.p-3.p-md-4.px-lg-5
          .titulo-sexto.color-acento-contenido
            h5 Figura 15.
            span Aplicación del divisor de voltaje
          figure.mb-2
            img.px-lg-3(src='@/assets/curso/temas/t5/fig15.svg', alt='El diagrama muestra un circuito eléctrico simple que incluye una fuente de voltaje (V) y dos resistencias, (R1) y (R2), en serie. En este circuito, la corriente (I) fluye a través de las resistencias, generando tensiones (V1) y (V2) en ellas, respectivamente.')  
          figcaption Fuente: Zambrano, (2019)
    
    p.text-center.mb-4 A continuación, se presentan las fórmulas correspondientes junto con el esquema ilustrativo para su aplicación:

    .row.justify-content-center.text-center.mb-5(data-aos="fade-down")
      .col-lg-5
        .subt2.mb-4.m-auto
          h3.mb-0.py-1.px-4 Fórmulas
        .tarjeta.bg5.p-3
          .row.justify-content-center
            .col-lg-6.fw-bold
              div.formula-container
                span.v2 V2
                span.equals = 
                .fraction
                  .numerator
                    span.r R2
                  .denominator 
                    span.r R1  + R2
                span.v V  
            .col-lg-6.fw-bold
              div.formula-container
                span.v2 V1
                span.equals = 
                .fraction
                  .numerator
                    span.r R2
                  .denominator 
                    span.r R1  + R2
                span.v V  

    .subt.mb-4(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-2
          img(src='@/assets/curso/temas/t7/subt.svg', alt='')
        .col-md-auto.col-10.ps-0
          h3.mb-0.text-white Divisor de corriente

    p Es un principio utilizado cuando se conectan dos o más resistencias en paralelo y se aplica un voltaje determinado. En este tipo de configuración, la corriente eléctrica se distribuye entre las ramas, de modo que una parte fluye a través de la resistencia 1 y otra parte a través de la resistencia 2, reuniéndose nuevamente al final del circuito.      

    .tarjeta.bg4.p-4.px-lg-5.mb-4
      h5.mb-0 Para determinar cuánta corriente circula por cada resistencia, se aplica la fórmula del divisor de corriente, la cual permite calcular la proporción de corriente que fluye por cada rama, dependiendo de los valores de las resistencias involucradas.

    p.text-center Antes de aplicar esta fórmula, es necesario calcular la resistencia total equivalente, ya que, al estar en paralelo, se utiliza la siguiente expresión:

    .row.justify-content-center.text-center.mb-5(data-aos="fade-down")
      .col-lg-3
        .tarjeta.bg5.fw-bold.p-3
          div.formula-container
            span.v2 RT
            span.equals = 
            .fraction
              .numerator
                span.r R2 x R2
              .denominator 
                span.r R1  + R2 
           

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
