<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Sistema eléctrico

    p El sistema eléctrico es el conjunto de equipos, instalaciones y redes necesarios para suministrar energía eléctrica a los consumidores, asegurando que esta llegue en la cantidad, calidad y momento requeridos.
    p.mb-4 Este sistema se organiza en varios subsistemas fundamentales:  

    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Figura 18.
      span Red de distribución eléctrica
    div.mb-4(data-aos='fade-right')
      figure.mb-2
        img(src='@/assets/curso/temas/t7/fig18.png', alt='La imagen ilustra el proceso de generación, transmisión, transformación, distribución y consumo de electricidad, comenzando desde una central eléctrica que produce energía a 22 kV y utilizando transformadores para elevar el voltaje hasta 220 kV para su transmisión a larga distancia; después, la electricidad se transforma nuevamente a 66 kV y posteriormente a 15 kV, facilitando su distribución en media y baja tensión, hasta alcanzar los usuarios finales que consumen la energía a niveles de 220/110 V.')  
      figcaption Fuente: Picco, (2014)  

    p.mb-0 Cada uno de estos subsistemas está compuesto por diversos elementos físicos e infraestructuras técnicas.
    p Desde el punto de vista técnico y económico, la energía eléctrica se genera, transmite y distribuye, en la mayoría de los casos, en forma trifásica, por su eficiencia en el transporte y utilización de la energía.

    TabsC.color-primario.mb-5(data-aos='fade-down')
      .py-3.py-md-4.py-lg-5.bg3(titulo="Generación")
        .row.justify-content-center
          .col-11
            p La energía eléctrica se produce en centrales eléctricas, instalaciones diseñadas para transformar energía primaria (como hidráulica, térmica, solar o eólica) en energía eléctrica. Esto se logra mediante una turbina que, al girar, acciona un alternador, el cual genera corriente alterna sinusoidal a voltajes intermedios, generalmente entre 6.000 y 23.000 voltios.
      .py-3.py-md-4.py-lg-5.bg3(titulo="Transmisión")
        .row.justify-content-center
          .col-11
            p La energía generada se transporta a largas distancias a través de la red de transmisión, que enlaza las centrales eléctricas con las áreas de consumo. Esta red debe estar interconectada mediante estructuras malladas que permiten el flujo de energía en múltiples direcciones, asegurando estabilidad y eficiencia en el sistema. Las líneas de transmisión operan a tensiones elevadas, generalmente superiores a 66.000 voltios, y son soportadas por torres metálicas de gran altura.
      .py-3.py-md-4.py-lg-5.bg3(titulo="Transformación - Subestaciones")
        .row.justify-content-center
          .col-11
            p Las subestaciones eléctricas son instalaciones que transforman el nivel de tensión de la energía para facilitar su transporte y distribución. Existen dos tipos principales:
            ul.lista-ul--color.fa-lista.tercer.ps-2.ps-lg-4
              li
                i.fas.fa-circle-check
                span.mb-0 Subestaciones elevadoras, ubicadas junto a las centrales generadoras, que aumentan la tensión para la transmisión.
              li
                i.fas.fa-circle-check
                span.mb-0 Subestaciones reductoras, ubicadas cerca de las zonas de consumo, que disminuyen la tensión para su distribución local.
            p Ambas están interconectadas por la red de transporte.    
      .py-3.py-md-4.py-lg-5.bg3(titulo="Distribución")
        .row.justify-content-center
          .col-11
            p La energía llega a los usuarios finales a través de la red de distribución, presente en zonas urbanas y rurales. Estas redes pueden ser:
            ul.lista-ul--color.fa-lista.tercer.ps-2.ps-lg-4
              li
                i.fas.fa-circle-check
                span.mb-0 Aéreas, de instalación más económica.
              li
                i.fas.fa-circle-check
                span.mb-0 Subterráneas, con mejor estética y menor impacto visual, pero de mayor costo.
            p La distribución opera en niveles de:
            ul.lista-ul--color.fa-lista.tercer.ps-2.ps-lg-4
              li
                i.fas.fa-circle-check
                span.mb-0 Alta Tensión (AT): entre 6.000 y 23.000 voltios.
              li
                i.fas.fa-circle-check
                span.mb-0 Baja Tensión (BT): típicamente 400/230 voltios, adecuada para el uso residencial y comercial.
      .py-3.py-md-4.py-lg-5.bg3(titulo="Consumo")
        .row.justify-content-center
          .col-11
            p Finalmente, en los centros de consumo, la energía es utilizada en baja o alta tensión, dependiendo del tipo de usuario y de la aplicación. Esto incluye desde hogares y oficinas hasta grandes industrias o centros tecnológicos.

    .subt.mb-4(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-2
          img(src='@/assets/curso/temas/t7/subt.svg', alt='')
        .col-md-auto.col-10.ps-0
          h3.mb-0.text-white Tipos de corriente dentro de un sistema eléctrico 
    
    p.mb-4 En la práctica, los dos tipos de corrientes eléctricas más comunes son: #[b corriente directa (DC)] o #[b continua] y #[b corriente alterna (AC)]. 
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6(data-aos="fade-right")
        .subt2.mb-4
          h3.mb-0.py-1.px-4 La corriente directa
        p Circula siempre en un solo sentido, es decir, del polo negativo al positivo de la fuente de fuerza electromotriz (FEM) que la suministra. Esa corriente mantiene siempre fija su polaridad, como es el caso de las pilas, baterías y dinamos.
        .tarjeta.bg4.p-4.px-lg-5
          h5.mb-0 Una fuente de fuerza electromotriz (FEM) es un dispositivo o sistema que proporciona energía eléctrica al circuito, generando una diferencia de potencial (voltaje) que pone en movimiento las cargas eléctricas.
      .col-lg-6(data-aos="fade-left")
        .bg-grad1.p-3.p-md-4.px-lg-5
          .titulo-sexto.color-acento-contenido
            h5 Figura 19.
            span Corriente directa
          figure.mb-2
            img(src='@/assets/curso/temas/t7/fig19.svg', alt='El gráfico ilustra el paso de la corriente directa, donde se presenta una línea horizontal constante en 110 voltios a lo largo del tiempo, indicando que el voltaje se mantiene fijo.')  
          figcaption Fuente: Corriente eléctrica, (2011) 

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6(data-aos="fade-right")
        .subt2.mb-4
          h3.mb-0.py-1.px-4 La corriente alterna
        p Se diferencia de la directa en que cambia su sentido de circulación periódicamente y, por tanto, su polaridad. Esto ocurre tantas veces como frecuencia en hercios (Hz) tenga esa corriente. A la corriente directa (DC), también se le llama “corriente continua”.
        .tarjeta.bg4.p-4.px-lg-5
          h5 Frecuencia (Hz) es el número de veces que se repite un ciclo en un segundo.
          h5.mb-0 Se mide en hercios (Hz), y 1 Hz equivale a 1 ciclo por segundo.
      .col-lg-6(data-aos="fade-left")
        .bg-grad1.p-3.p-md-4.px-lg-5
          .titulo-sexto.color-acento-contenido
            h5 Figura 20.
            span Corriente alterna
          figure.mb-2
            img(src='@/assets/curso/temas/t7/fig20.svg', alt='El gráfico ilustra el paso de corriente alterna, donde se presenta una forma de onda que varía entre 110 y -110 voltios, reflejando la naturaleza fluctuante de esta corriente a lo largo del tiempo.')  
          figcaption Fuente: Corriente eléctrica, (2011) 

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t7/1.jpg')})`}")
      .bloque-texto-g__texto.p-4
        br
        p Comprender los fundamentos de la electricidad es clave para el diseño y mantenimiento de instalaciones eléctricas domiciliarias seguras y eficientes. El dominio de conceptos como corriente, voltaje, resistencia, así como la aplicación de leyes fundamentales y el uso adecuado de elementos del circuito, permite aprendiz desarrollar habilidades prácticas esenciales; este conocimiento no solo fortalece la comprensión teórica, sino que también prepara para enfrentar los retos del entorno eléctrico residencial con criterio, seguridad y responsabilidad.
        br
        br

</template>

<script>
export default {
  name: 'Tema7',
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
