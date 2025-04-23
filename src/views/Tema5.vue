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
              img(src='@/assets/curso/temas/t5/subt.svg', alt='')
            .col-md-auto.col-10.ps-0
              h3.mb-0.text-white El divisor de tensión o divisor de voltaje
        p Es un principio fundamental en el análisis de circuitos eléctricos. Permite calcular el voltaje que cae sobre una o varias resistencias conectadas en serie, a partir del voltaje total aplicado al circuito.
        p Este método se aplica directamente cuando se trabaja con dos resistencias en serie. Si el circuito contiene más de dos resistencias, se debe aplicar el divisor de voltaje de forma progresiva, agrupando resistencias de dos en dos y resolviendo paso a paso hasta alcanzar la resistencia de interés.
        .tarjeta.bg4.p-4.px-lg-5
          h5.mb-0 El divisor de voltaje es especialmente útil cuando no se dispone del valor de la corriente eléctrica en el circuito, pero sí se conocen los valores de las resistencias. En estos casos, no es posible aplicar directamente la Ley de Ohm, por lo que el divisor de tensión se convierte en una herramienta clave para determinar los voltajes parciales en cada componente.
      .col-lg-6.col-md-8.col-10(data-aos="fade-left")
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
            .col-lg-6.col-md-6.col-6.fw-bold
              div.formula-container
                span.v2 V2
                span.equals = 
                .fraction
                  .numerator
                    span.r R2
                  .denominator 
                    span.r R1  + R2
                span.v V  
            .col-lg-6.col-md-6.col-6.fw-bold
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
        .col-md-auto.col-3
          img(src='@/assets/curso/temas/t5/subt.svg', alt='')
        .col-md-auto.col-9.ps-0
          h3.mb-0.text-white Divisor de corriente

    p Es un principio utilizado cuando se conectan dos o más resistencias en paralelo y se aplica un voltaje determinado. En este tipo de configuración, la corriente eléctrica se distribuye entre las ramas, de modo que una parte fluye a través de la resistencia 1 y otra parte a través de la resistencia 2, reuniéndose nuevamente al final del circuito.      

    .tarjeta.bg4.p-4.px-lg-5.mb-4
      h5.mb-0 Para determinar cuánta corriente circula por cada resistencia, se aplica la fórmula del divisor de corriente, la cual permite calcular la proporción de corriente que fluye por cada rama, dependiendo de los valores de las resistencias involucradas.

    p.text-center Antes de aplicar esta fórmula, es necesario calcular la resistencia total equivalente, ya que, al estar en paralelo, se utiliza la siguiente expresión:

    .row.justify-content-center.text-center.mb-5(data-aos="fade-down")
      .col-lg-3.col-md-4.col-7
        .tarjeta.bg5.fw-bold.p-3
          div.formula-container
            span.v2 RT
            span.equals = 
            .fraction
              .numerator
                span.r R2 x R2
              .denominator 
                span.r R1  + R2 
           
    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 16.
                span Ejemplo divisor de corriente
            .col-lg-6.col-md-8
              figure.mb-2
                img(src='@/assets/curso/temas/t5/fig16.svg', alt='La imagen presenta un diagrama de un circuito eléctrico en serie y paralelo, donde la fuente de voltaje (V_T) alimenta múltiples ramas. Las corrientes (I_T), (I_1), y (I_2) fluyen a través de las resistencias (R_1) y (R_2), mostrando cómo la corriente se divide en diferentes trayectorias. Las flechas indican la dirección del flujo de corriente, lo que es crucial para el entendimiento de la polaridad y el funcionamiento del circuito.')  
              figcaption Fuente: Zambrano, (2019)

    p.text-center Después se calcula la corriente total:

    .row.justify-content-center.text-center.mb-5(data-aos="fade-down")
      .col-lg-2.col-md-3.col-5
        .tarjeta.bg5.fw-bold.p-3
          div.formula-container
            span.v2 IT
            span.equals = 
            .fraction
              .numerator
                span.r V
              .denominator 
                span.r RT

    p.text-center Donde V es el voltaje total que se le proporciona al circuito.

    p.text-center Para calcular el valor de la corriente que pasa en cada una de las resistencias, se tiene la fórmula de división de corriente.

    p.text-center Para la Corriente que pasa a través de la resistencia 1:

    .row.justify-content-center.text-center.mb-4(data-aos="fade-down")
      .col-lg-4.col-md-6.col-10
        .tarjeta.bg5.fw-bold.p-3
          div.equation-box
            span.current-i2 I2
            span.equation-symbol =
            span.current-it IT
            span.parenthesis-left (
            div.division-part
              div.top-section
                span.resistance R1 
              div.bottom-section
                span.resistance R1 + R2
            span.parenthesis-right )

    p.text-center.mb-5 La suma de ambas corrientes debe ser igual a la corriente total.


    .subt.mb-4(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-2
          img(src='@/assets/curso/temas/t5/subt.svg', alt='')
        .col-md-auto.col-10.ps-0
          h3.mb-0.text-white Condensadores e inductores
    
    p.mb-4 Comprender el funcionamiento de los condensadores e inductores es fundamental en el estudio de los circuitos eléctricos, ya que ambos componentes desempeñan un papel clave en el almacenamiento y gestión de la energía eléctrica.

    .subt2.mb-4
      h3.mb-0.py-1.px-4 Condensadores

    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center.mb-3
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 17.
                span Condensadores
            .col-lg-6.col-md-8
              figure
                img(src='@/assets/curso/temas/t5/fig17.png', alt='La figura presenta una variedad de condensadores de diferentes formas y tamaños, dispuestos sobre una superficie de madera. También se encuentran algunas resistencias electrónicas, lo que sugiere un conjunto de componentes utilizados en circuitos eléctricos o electrónicos.')  

    p.mb-4 Un condensador es un componente electrónico que almacena energía en forma de campo eléctrico. Está formado por dos placas metálicas paralelas separadas por un material dieléctrico que actúa como aislante. Su capacidad, medida en faradios (F), indica la cantidad de carga que puede almacenar por unidad de voltaje. Dado que el faradio es una unidad muy grande, en la práctica se utilizan submúltiplos como el microfaradio (µF), nanofaradio (nF) y picofaradio (pF).

    .tarjeta.bg-grad2.p-3.mb-5(data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-2
          img.px-lg-2.m-auto(src="@/assets/curso/temas/t5/cta.png")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.texto-blanco.mb-1 Condensadores eléctricos
              p.t-color-sec.mb-0.pe-lg-3 Para ampliar esta información descargue el siguiente anexo donde encontrará información clave sobre condensadores eléctricos.
            .col-sm-auto
              a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Condensadores_electricos.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t5/tarj1.png', alt='')
          h4.tit.mb-3.py-1.pb-0.px-4 Tensión de trabajo
          p.mb-0 Es el valor máximo de voltaje que puede soportar un condensador sin dañarse. Esta capacidad depende del tipo de dieléctrico y su grosor. Si se aplica una tensión superior a la especificada, el dieléctrico puede romperse, provocando un cortocircuito o incluso una explosión. Por eso, siempre se debe seleccionar un condensador cuya tensión de trabajo sea superior a la máxima que se espera en el circuito.
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t5/tarj2.png', alt='')
          h4.tit.mb-3.py-1.pb-0.px-4 Tolerancia
          p.mb-0 Al igual que en las resistencias, la tolerancia indica el margen de error entre la capacidad real del condensador y la que se indica en su carcasa. Por ejemplo, un condensador de 100 µF con una tolerancia del ±10% puede tener una capacidad real entre 90 µF y 110 µF.
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t5/tarj3.png', alt='')
          h4.tit.mb-3.py-1.pb-0.px-4 Polaridad
          p.mb-0 Algunos condensadores, especialmente los electrolíticos y aquellos con capacidad superior a 1 µF, tienen polaridad, es decir, deben conectarse respetando los terminales positivo y negativo. Si se invierte la polaridad, pueden deteriorarse o explotar. En cambio, los condensadores de menor capacidad (inferiores a 1 µF) suelen ser no polarizados, por lo que pueden conectarse en cualquier sentido.

    .subt2.mb-4(data-aos="fade-right")
      h3.mb-0.py-1.px-4 Inductores

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t5/1.jpg')})`}")
      .bloque-texto-g__texto.p-4.py-lg-5
        p Los inductores, también conocidos como bobinas, son componentes pasivos y lineales capaces de almacenar y liberar energía mediante fenómenos asociados a los campos magnéticos; cuando una corriente eléctrica circula a través de un conductor, se genera un campo magnético alrededor de este. Las líneas de fuerza de dicho campo se expanden desde el centro del conductor hacia el exterior, atravesando primero el propio conductor y luego el aire circundante.
        br
        br 
        p.mb-0 Un inductor está formado por un arrollamiento de hilo conductor. La inductancia que produce depende directamente del número de espiras, del diámetro de estas y de la permeabilidad del material presente en el interior del arrollamiento. A su vez, es inversamente proporcional a la longitud de la bobina.   


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
