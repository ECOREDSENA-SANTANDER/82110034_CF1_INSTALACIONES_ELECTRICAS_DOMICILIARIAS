<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Leyes fundamentales en electricidad

    p.mb-5 Las siguientes leyes son esenciales para el análisis y diseño de circuitos eléctricos, especialmente cuando se trata de configuraciones complejas; su aplicación adecuada permite calcular diversos parámetros eléctricos y asegurar el funcionamiento eficiente de los circuitos.

    .subt.mb-4(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-3
          img(src='@/assets/curso/temas/t3/subt.svg', alt='')
        .col-md-auto.col-9.ps-0
          h3.mb-0.text-white Ley de Ohm

    p.mb-4 Según García (2023), “la corriente eléctrica que circula por un conductor es directamente proporcional al voltaje aplicado e inversamente proporcional a la resistencia de este”. Esta relación puede expresarse mediante la fórmula:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-2.col-md-3.col-4.mb-3
        .tarjeta.bg5.p-3.py-md-4.text-center
          h3.mb-0.font-italic I=V/R
      .col-lg-2.col-md-3.col-4.mb-3
        .tarjeta.bg5.p-3.py-md-4.text-center
          h3.mb-0.font-italic V=IR
      .col-lg-2.col-md-3.col-4.mb-3
        .tarjeta.bg5.p-3.py-md-4.text-center
          h3.mb-0.font-italic R=V/I
    
    p.text-center.mb-4 Donde:      

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t3/tarj1-1.png', alt='')
          p.mb-0 Corriente eléctrica (en amperios).
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t3/tarj1-2.png', alt='')
          p.mb-0 Voltaje o diferencia de potencial (en voltios).
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t3/tarj1-3.png', alt='')
          p.mb-0 Resistencia del conductor (en ohmios).


    .subt.mb-4(data-aos="fade-right")
      .row.align-items-center
        .col-md-auto.col-3
          img(src='@/assets/curso/temas/t3/subt.svg', alt='')
        .col-md-auto.col-9.ps-0
          h3.mb-0.text-white Leyes de Kirchhoff

    p.mb-5 Formuladas por Gustav Robert Kirchhoff (1824–1887), estas leyes son fundamentales para el análisis de circuitos eléctricos, ya que permiten resolver circuitos con múltiples mallas y nodos.

    .subt2.mb-4(data-aos="fade")
      h3.mb-0.py-1.px-4 a) Ley de corrientes de Kirchhoff (LCK) o Ley de nodos

    p Establece que la suma de las corrientes que entran a un nodo (punto de conexión en un circuito) es igual a la suma de las corrientes que salen de él. Es decir, la corriente no se acumula en un nodo, lo cual refleja el principio de conservación de la carga eléctrica.

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-5.col-md-10.mb-3
        .tarjeta.bg5.p-3.py-md-4.text-center
          h3.mb-0 (Suma algebraica de I) Σ I = 0 (en la unión)

    p.mb-5 Asumiendo que las corrientes que entran al nodo son positivas (+) y las que salen son negativas (−), la suma algebraica de las corrientes en un nodo siempre será cero.      

    
    .subt2.mb-4(data-aos="fade")
      h3.mb-0.py-1.px-4 b) Ley de voltajes de Kirchhoff (LVK) o Ley de mallas

    p Afirma que, en cualquier malla cerrada de un circuito, la suma algebraica de todas las tensiones (subidas y caídas de potencial) es igual a cero. Esto se debe al principio de conservación de la energía eléctrica.

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-11.mb-3
        .tarjeta.bg5.p-3.py-md-4.text-center
          h3.mb-0 (Suma algebraica de E) Σ E - Σ I*R = 0. (Suma algebraica de las caídas I*R, en la malla cerrada)

    p.text-center Donde:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t3/tarj2-1.png', alt='')
          p.mb-0 Representa las fuentes de voltaje o fuerza electromotriz (FEM).
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t3/tarj2-2.png', alt='')
          p.mb-0 Representa la caída de tensión en cada resistencia.
      .col-lg-4.col-md-6.mb-3
        .tarjeta.tarj-hover.text-center.p-4.h-100
          img.mb-0(src='@/assets/curso/temas/t3/tarj2-3.png', alt='')
          p.mb-0 Las subidas de potencial se consideran positivas (+), y las caídas, negativas (−).

    p Estas leyes permiten plantear ecuaciones que describen el comportamiento del circuito, facilitando su análisis y resolución. Un ejemplo es: 1k Ω      

    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 4.
                span Suma corrientes 
            .col-lg-5.col-md-8
              figure.mb-2
                img(src='@/assets/curso/temas/t3/fig4.svg', alt='La figura representa un circuito resistivo con un nodo central donde convergen tres corrientes: I1, I2 e I3. Cada rama contiene una resistencia de 1k. El diagrama ilustra la aplicación de la Ley de Kirchhoff para corrientes, indicando que la suma de las corrientes que entran al nodo es igual a la suma de las que salen.')  
              figcaption Fuente: Polverini, (2022)

    p Las flechas representan la dirección del flujo de la corriente en el nodo. I1 entra a la unión, considerando que I2 e I3 salen. Si I1 fuera 20 A e I3 fuera 5 A, I2 tendría 15 A, según la ley de corrientes de I1=I2 + I3.

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-7.mb-3
        .tarjeta.bg4.p-4.text-center
          h5.mb-0 La ley de Kirchhoff para los voltajes es, la suma de voltajes alrededor de un circuito cerrado es igual a cero. Esto también puede expresarse como la suma de voltajes de un circuito cerrado es igual a la suma de voltajes de las fuentes de tensión.

    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 5.
                span Suma de corrientes en circuito cerrado
            .col-lg-4.col-md-8
              figure.mb-2
                img(src='@/assets/curso/temas/t3/fig5.svg', alt='La figura representa un circuito cerrado con una fuente de voltaje de 10V y tres resistencias conectadas en serie: R1, R2 y R3. A cada resistencia le corresponde una caída de tensión identificada como V1, V2 y V3, respectivamente. El esquema ilustra el principio de la Ley de corrientes de Kirchhoff, donde la suma de las caídas de tensión en las resistencias es igual al voltaje total suministrado por la fuente. ')  
              figcaption Fuente: Polverini, (2022)

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-10.mb-3
        .tarjeta.bg4.p-4.text-center
          h5.mb-0 La suma de las caídas de voltaje en R1, R2 y R3 deben ser igual a 10 V, es decir, 10 V=V1+V2+V3.

    .row.bgc-3.align-items-center.p-2.p-md-3.mb-4(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center
            .col-lg-12
              .titulo-sexto.color-acento-contenido
                h5 Figura 6.Suma de las caídas de voltaje
                span 
            .col-lg-5.col-md-8
              figure.mb-2
                img(src='@/assets/curso/temas/t3/fig6.svg', alt='La figura representa un circuito eléctrico con tres resistencias (R1, R2 y R3) conectadas a dos fuentes de voltaje de 15 V y 20 V. Se indican las corrientes I1, I2 e I3, así como el valor de 0.5 A en una de las ramas. El circuito permite analizar la aplicación de la Ley de Kirchhoff para voltajes, donde la suma de las caídas de tensión en cada malla es igual a la suma de las fuentes de voltaje en esa misma malla.')  
              figcaption Fuente: Polverini, (2022)

    p Las corrientes de I2 e I3 y la resistencia desconocida R3 centran todos los cálculos, usando la teoría básica de la corriente continua. La dirección del flujo de la corriente está indicada por las flechas.

    .row.bgc-4.align-items-center.p-2.p-md-3
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center
        
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-4.col-md-7.col-10.mb-3.mb-lg-0(data-aos="fade-right")
              img(src='@/assets/curso/temas/t3/1.png', alt='')
            .col-lg-8(data-aos="fade-left")
              ul.lista-ul--color.sec2.fa-lista.mb-0
                li
                  i.fas.fa-circle-check
                  span.mb-0 El voltaje en el lado izquierdo (la resistencia R1 de 10 Ω), está saliendo del terminal superior de la Resistencia.
                li
                  i.fas.fa-circle-check
                  span.mb-0 La diferencia de potencial (DDP) en esta resistencia R1 es de I1xR o sea, 5 voltios. Esto está en oposición de los 15 voltios de la batería.
                li
                  i.fas.fa-circle-check
                  span.mb-0 Por la ley de Kirchhoff del voltaje, la diferencia de potencial (DDP) por la resistencia R2 de 10 Ω es así 15-5 o sea, 10 voltios.
                li
                  i.fas.fa-circle-check
                  span.mb-0 Usando la ley Ohm, la corriente a través de la resistencia R2 10 Ω es entonces (V/R) 1 amperio.
                li
                  i.fas.fa-circle-check
                  span.mb-0 Usando la ley de Kirchhoff de la corriente y ahora conociendo el I1 e I3, el I2 se encuentra como I3=I1+I2  por consiguiente el amperaje de I2= 0.5 A.
                li
                  i.fas.fa-circle-check
                  span.mb-0 De nuevo, usando la ley de Kirchhoff del voltaje, la diferencia de potencial (DDP) para R3 puede calcularse como, 20 = I2xR3 +10. El voltaje por R3 (el I2xR3 ) es entonces 10 voltios. El valor de R3 es (V/I)o 10/0.5o 20Ω.

          .row.justify-content-center
            .col-lg-12
              .subt2.mb-4(data-aos="fade")
                h3.mb-0.py-1.px-4 Ley de Joule - potencia calorífica
              p La corriente eléctrica puede producir calor o trabajo, dicho trabajo (W) será igual al producto de la carga (Q) por la diferencia de potencial (V) entre los dos puntos:  

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-5.col-md-8.col-11.mb-3
        .tarjeta.bg4.p-4.text-center
          h5 W=VxQ
          h5.mb-0 Por otro lado, sabemos que Q=Ixt
          h5.mb-0 entonces: W=VxIxt
          h5.mb-0 Por la ley de Ohm sabemos que V=RxI
          h5.mb-0 entonces: W=(RxI)xIxt
          h5.mb-0 W = R x I ^2 x t

    p Donde Q es la cantidad de calor generado, I es la intensidad de la corriente, R es la resistencia del conductor y t es el tiempo que dura la corriente.

    p.mb-5 La fórmula anterior indica que el trabajo realizado por el campo eléctrico para mover las cargas eléctricas a lo largo de un conductor se transforma íntegramente en calor. Este trabajo depende de la intensidad de la corriente que circula por el conductor, la resistencia que ofrece este al paso de corriente y el tiempo durante el cual circula.

    .subt2.mb-4(data-aos="fade")
      h3.mb-0.py-1.px-4 Ley de Watt - Potencia eléctrica

    p Es la cantidad de energía eléctrica o trabajo, que se transporta o que se consume en una determinada unidad de tiempo.

    p Si la tensión se mantiene constante, la potencia es directamente proporcional a la corriente. Para calcular la potencia en Watts se puede utilizar la fórmula:   

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-2.col-md-3.col-4
        .tarjeta.bg4.p-4.text-center
          h5.mb-0 P=VxI 

    p.text-center Donde:

    p.mb-0.text-center P: potencia.
    p.mb-0.text-center I: corriente. 
    p.text-center V: voltaje.



</template>

<script>
export default {
  name: 'Tema3',
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
