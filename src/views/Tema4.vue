<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Elementos de un circuito y resistencias


    .row.bgc-2.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center.align-items-center
            .col-12
              .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4
                .bloque-texto-g__img(
                  :style="{'background-image':`url(${require('@/assets/curso/temas/t4/1.jpg')})`}")
                .bloque-texto-g__texto.p-4.py-lg-5
                  br
                  p.mb-5 #[b ¿Qué es un circuito eléctrico?] Un circuito eléctrico es un conjunto de elementos interconectados de manera adecuada que permite el flujo de electrones, es decir, el paso de la corriente eléctrica. Para que este flujo se produzca, es necesario que el circuito esté cerrado y cuente con los componentes básicos que lo hacen funcionar correctamente.
                  br
                  br

          p.text-center A continuación, se describen sus elementos principales:

    AcordionA.mb-5(tipo="b" clase-tarjeta="bg-trans tipo-b" data-aos="fade-down")
      .row(titulo="Hilo conductor")
        .col-12
          p Es el medio por el cual circula la corriente eléctrica, está fabricado con materiales que permiten el paso de los electrones con facilidad, ya que ofrecen poca resistencia al flujo eléctrico. Estos materiales, como el cobre o el aluminio, contienen electrones libres que facilitan el movimiento de la carga eléctrica a través del circuito.
      .row(titulo="Generador o acumulador")
        .col-12
          p Es el componente que proporciona la energía necesaria para que los electrones circulen por el circuito. Su función principal es mantener una diferencia de potencial (voltaje) entre los extremos del conductor.
          p Tipos de generadores:
          ul.lista-ul--color.sec2.fa-lista.mb-0
            li
              i.fas.fa-circle-check
              span.mb-0 Generadores primarios: se utilizan una sola vez. Ejemplo: pilas.
            li
              i.fas.fa-circle-check
              span.mb-0 Generadores secundarios: son recargables y pueden usarse varias veces. Ejemplo: baterías o acumuladores.
      .row(titulo="Receptores")
        .col-12
          p Son los dispositivos que reciben la energía eléctrica y la transforman en otro tipo de energía útil. De acuerdo con la energía que generan, se clasifican en:
          ul.lista-ul--color.sec2.fa-lista.mb-0
            li
              i.fas.fa-circle-check
              span.mb-0 Térmicos: transforman la energía eléctrica en calor (ej. resistencias).
            li
              i.fas.fa-circle-check
              span.mb-0 Electroquímicos: generan reacciones químicas.
            li
              i.fas.fa-circle-check
              span.mb-0 Mecánicos: transforman la energía eléctrica en movimiento.
            li
              i.fas.fa-circle-check
              span.mb-0 Lumínicos: generan luz (ej. bombillas).
            li
              i.fas.fa-circle-check
              span.mb-0 Acústicos: producen sonido (ej. altavoces).
      .row(titulo="Elementos de control o maniobra")
        .col-12
          p Estos elementos permiten interrumpir, habilitar o modificar el flujo de corriente eléctrica dentro del circuito, facilitando su control.
          ul.lista-ul--color.sec2.fa-lista.mb-0
            li
              i.fas.fa-circle-check
              span.mb-0 Pulsador: Abre o cierra el circuito solo mientras está presionado.
            li
              i.fas.fa-circle-check
              span.mb-0 Interruptor: Abre o cierra el circuito de forma permanente hasta que se accione nuevamente.
            li
              i.fas.fa-circle-check
              span.mb-0 Conmutador: Permite controlar el encendido o apagado del circuito desde diferentes puntos. Un tipo especial es el conmutador de cruce, que invierte la polaridad del circuito, comúnmente usado para cambiar el sentido de giro de los motores.
      .row(titulo="Elementos pasivos")
        .col-12
          p Son aquellos componentes que no generan energía, sino que la absorben o consumen cuando la corriente circula por ellos. Estos elementos provocan una caída de tensión entre sus extremos y disipan energía, generalmente en forma de calor. Ejemplos típicos de elementos pasivos son las resistencias, bobinas y condensadores.


    .subt.mb-5(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-3
          img(src='@/assets/curso/temas/t4/subt.svg', alt='')
        .col-md-auto.col-9.ps-0
          h3.mb-0.text-white Resistencias eléctricas y su identificación

    .subt2.mb-4(data-aos="fade")
      h3.mb-0.py-1.px-4 Resistencias eléctrica

    p Una resistencia o resistor es un componente pasivo que se encarga de oponer el paso de la corriente eléctrica en un circuito. Esta oposición genera una diferencia de potencial (voltaje) entre sus terminales.

    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 7.
                span Resistencia eléctrica
            .col-lg-8.col-md-8
              figure.mb-2
                img(src='@/assets/curso/temas/t4/fig7.jpg', alt='La imagen presenta una resistencia, que es un componente diseñado para limitar el flujo de corriente eléctrica en un circuito. Tiene un cuerpo cilíndrico con bandas de colores que indican su valor resistivo.')  


    .subt2.mb-4(data-aos="fade")
      h3.mb-0.py-1.px-4 Código de colores 

    p Para identificar con facilidad el valor de una resistencia, se utiliza un código de colores. Este consiste en una serie de bandas pintadas sobre el cuerpo del resistor, donde cada color representa un número específico. Al interpretar estas bandas según una tabla estándar, se puede determinar el valor de la resistencia en ohmios (Ω).  

    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 8.
                span Código de colores
            .col-lg-8
              figure.mb-2
                img(src='@/assets/curso/temas/t4/fig8.svg', alt='La figura expone un código de colores asociado con valores numéricos y multiplicadores utilizados para identificar resistencias electrónicas: el marrón representa 1 y tiene un multiplicador de X10; el rojo es 2 con X100; el naranja es 3 con X1.000; el amarillo es 4 con X10.000; el verde es 5 con X100.000; el azul es 6 x 1.000.000; el violeta es 7; el gris es 8 con X0.1; y el blanco es 9 con X0.01. Además, se indican valores sin color, como el plateado (+/-1) y el dorado (+/-2), junto con sus márgenes de error.')  
              figcaption Fuente: Zambrano, (2019)
            .col-lg-4.d-none.d-lg-block
              img(src='@/assets/curso/temas/t4/2.png', alt='')

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-8.mb-3
        .tarjeta.bg4.p-4
          h5.mb-0 Ejemplo. 
          h5.mb-0 Si los colores son: marrón, negro, rojo, oro, su valor en ohmios (ver Ley de Ohm) es: 
          h5.mb-0 10 x 100 = 1000 = 1K.    
          h5.mb-0 Tolerancia de 5 %.


    .subt.mb-4(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-3
          img(src='@/assets/curso/temas/t4/subt.svg', alt='')
        .col-md-auto.col-9.ps-0
          h3.mb-0.text-white Asociación de resistencias

    p.mb-5 En los circuitos eléctricos, las resistencias pueden conectarse de diferentes maneras según la funcionalidad requerida. Las dos formas más comunes de asociación son en serie y en paralelo, cada una con características específicas que afectan el comportamiento de la corriente y el voltaje en el circuito. Comprender estas configuraciones es fundamental para el diseño y análisis de sistemas eléctricos y electrónicos tal como lo expone Gómez Palencia (2013).

    
    .subt2.mb-4(data-aos="fade")
      h3.mb-0.py-1.px-4 Resistencias en serie

    .row.justify-content-center.mb-5
      .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
        p En un circuito en serie donde las resistencias se colocan una seguida de la otra de tal modo que la corriente, deberá fluir primero por una de ellas para llegar a la siguiente, esto implica que el valor de la resistencia total del circuito sea la suma de todas ellas.  
        .tarjeta.bg5.p-4.text-center
          h3.mb-0.font-italic Rt = R1+ R2 + R3
      .col-lg-6.col-md-9.px-lg-5(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Figura 9.
          span Resistencia en serie
        figure.mb-2
          img(src='@/assets/curso/temas/t4/fig9.svg', alt='La imagen presenta un circuito en serie compuesto por tres resistencias, R1, R2 y R3; la resistencia total (Rt) se calcula sumando las resistencias individuales, es decir, Rt = R1 + R2 + R3.')  
    

    .row.justify-content-between.align-items-center.mb-5
      .col-lg-7.mb-3.mb-lg-0(data-aos="fade-right")
        .subt2.mb-4
          h3.mb-0.py-1.px-4 Resistencias en paralelo
        p En un circuito en paralelo las resistencias se colocan según se indica en la siguiente figura, de esta manera la corriente eléctrica llega a todas las resistencias a la vez, aunque la intensidad de la corriente es mayor por el resistor de menor valor. En este caso la resistencia total del circuito se puede obtener utilizando la ecuación que se presenta.
        .tarjeta.bg5.p-4.text-center          
          .outer-container
            .math-expression
              .ratio-block
                .upper-element
                  span.math-number 1
                .lower-element
                  span.resistance-label Rt    
              span.math-operator =               
              .ratio-block
                .upper-element
                  span.math-number 1
                .lower-element 
                  span.resistance-label R1            
              span.math-operator +               
              .ratio-block
                .upper-element
                  span.math-number 1
                .lower-element
                  span.resistance-label R2              
              span.math-operator +               
              .ratio-block
                .upper-element
                  span.math-number 1
                .lower-element
                  span.resistance-label R3
      .col-lg-4.col-md-7(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Figura 10.
          span Resistencia en paralelo
        figure.mb-2
          img(src='@/assets/curso/temas/t4/fig10.svg', alt='La figura representa un arreglo de resistencias en paralelo, conformado por tres resistencias: R1, R2 y R3. Todas están conectadas entre los mismos dos puntos, lo que permite que la corriente se divida entre las tres ramas. La resistencia equivalente total del sistema se denota como Rt y es menor que el valor de la menor resistencia individual del conjunto.')  
                

    .row.justify-content-between.mb-5
      .col-lg-7.mb-3.mb-lg-0(data-aos="fade-right")
        .subt2.mb-4
          h3.mb-0.py-1.px-4 Circuitos combinados
        .tarjeta.bg10.p-4
          p.mb-0 En un circuito en paralelo las resistencias se colocan según se indica en la siguiente figura, de esta manera la corriente eléctrica llega a todas las resistencias a la vez, aunque la intensidad de la corriente es mayor por el resistor de menor valor. En este caso la resistencia total del circuito se puede obtener utilizando la ecuación que se presenta.
      .col-lg-4.col-md-7(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Figura 11.
          span Resistencia en circuito combinado
        figure.mb-2
          img(src='@/assets/curso/temas/t4/fig11.svg', alt='La figura representa un circuito combinado que integra resistencias en paralelo y en serie. R1 y R2 están en paralelo, conectadas en serie con R3. Esta combinación se enlaza en paralelo con R4 y R5, y finalmente todo el conjunto está en serie con R6. La resistencia total equivalente del sistema se denota como Rt. Este tipo de configuración permite analizar la interacción entre diferentes arreglos de resistencias dentro de un mismo circuito.')  

    .tarjeta.bg11.mb-5(data-aos="fade")
      .row.justify-content-center
        .col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t4/3.png', alt='')
        .col-lg-7       
          .p-4
            p.text-center.text-white Se puede iniciar por los circuitos más sencillos como resolver R 1-2, que representa la resistencia total entre R1 y R2, como están en paralelo.
            .tarjeta.bg5.p-4.text-center.text-dark.mb-4
              h3.mb-0.font-italic 1 / R₁₋₂ = 1 / R₁ + 1 / R₂
            p.text-center.text-white Combinando el resultado anterior con R3 y teniendo en cuenta que se trata de un circuito en serie.
            .tarjeta.bg5.p-4.text-center.text-dark.mb-4
              h3.mb-0.font-italic R₁₋₂₋₃ = R₁₋₂ + R₃
            p.text-center.text-white El circuito va quedando más pequeño, como se expone a continuación:


    .tarjeta.bg3.mb-5(data-aos="fade-down")
      .row.justify-content-center
        .col-lg-4.col-md-7
          .p-3
            .titulo-sexto.color-acento-contenido
              h5 Figura 12.
              span Resistencias en serie (R4 y R5)
            figure
              img.px-lg-3(src='@/assets/curso/temas/t4/fig12.svg', alt='La imagen representa un circuito eléctrico en un esquema de conexión de componentes conectados en paralelo (R1-2-3 y R4-R5). La resistencia total del circuito (R-t) se calcula sumando las resistencias en serie y utilizando la fórmula clásica para resistencias en paralelo, lo que permite determinar el comportamiento eléctrico del circuito completo.')  
        .col-lg-4
          .bg10.h-100.p-4
            p.text-center Nuevamente se presenta un circuito en serie entre R4 y R5, entonces.
            .tarjeta.bg5.p-4.text-center.mb-4
              h3.mb-0.font-italic R₄₋₅ = R₄ + R₅
            p.text-center.mb-4 De tal modo que se suprime y se reemplaza por R 4-5.
        .col-lg-4.col-md-9
          .p-3
            .titulo-sexto.color-acento-contenido
              h5 Figura 13.
              span Resistencias en paralelo (R1-2-3 y R4-5)
            figure
              img.w-50.m-auto(src='@/assets/curso/temas/t4/fig13.svg', alt='El circuito presenta una configuración en la que se tiene una residencia equivalente R1-2-3 conectada en paralelo con una resistencia equivalente R4-5. Ambas resistencias equivalentes están conectadas en serie con R6, formando la resistencia total Rt del circuito.')  

    .row.justify-content-center.mb-5
      .col-lg-6(data-aos="fade-right")
        p Se evidencia que cada vez la malla del circuito se va reduciendo, sucede que es una forma sencilla de resolverlo por pasos, con la práctica no será necesario hacerlo ya que se podrá resolver mentalmente.        
        p Ahora se resuelve el circuito en paralelo para obtener R 1…5.
        .tarjeta.bg5.p-4.text-center.mb-4
          h3.mb-0.font-italic 1 / R₁…₅ = 1 / R₁₋₂₋₃ + 1 / R₄₋₅
        p Finalmente se obtiene el circuito más sencillo de todos y es un circuito en serie, el cual proporciona la resistencia total.
      .col-lg-4.col-md-10(data-aos="fade-left")
        .bg3.p-4.h-100
          .titulo-sexto.color-acento-contenido
            h5 Figura 14.
            span Resistencia en serie (R1...5 y R6) 
          figure
            img.w-50.m-auto(src='@/assets/curso/temas/t4/fig14.svg', alt='En el circuito representado,  las resistencias R1, R2, R3, R4 y R5 forman una resistencia equivalente R1-5 que esta conectada en serie a una resistencia R6 y que su resistencia total se denota como Rt.')  

    
    .row.justify-content-center
      .col-lg-4.col-md-8
        .tarjeta.bg11.p-4
          h5.text-center.text-white.mb-4 El cálculo final sería como sigue:
        .row.justify-content-center.mt-n1
          .col-lg-9.col-md-7.col-9
            .tarjeta.bg5.p-4.text-center
              h3.mb-0.font-italic Rt = R₁…₅ + R₆

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
