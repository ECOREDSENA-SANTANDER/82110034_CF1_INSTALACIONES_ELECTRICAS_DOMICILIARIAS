<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Fundamentos esenciales de electricidad
        
      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4(data-aos="fade-down")
        .bloque-texto-g__img(
          :style="{'background-image':`url(${require('@/assets/curso/temas/t1/1.jpg')})`}")
        .bloque-texto-g__texto.p-4.py-lg-5
          p.mb-0 La electricidad es un fenómeno físico originado por la presencia y el movimiento de cargas eléctricas, principalmente los electrones. Se manifiesta en diferentes formas de energía como la térmica, mecánica, luminosa y química, lo que la convierte en una herramienta indispensable en la vida cotidiana, especialmente en el hogar, donde se utiliza para iluminación, calefacción y funcionamiento de electrodomésticos.

      .tarjeta.bg6.p-3.mb-5(data-aos="fade-down")
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-2
            img.px-lg-2.m-auto(src="@/assets/curso/temas/t5/cta.png")
          .col.texto-blanco
            h4.mb-1 Para ampliar esta información diríjase a los siguientes enlaces donde encontrará información clave sobre:
            .row.justify-content-between.align-items-center.mb-3
              .col.mb-3.mb-sm-0
                p.mb-0.pe-lg-3 Conceptos y leyes fundamentales de la electricidad
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Conceptos_y_leyes_de_la_electricidad.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                p.mb-0.pe-lg-3 Las transformaciones de la energía
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Las_transformaciones_de_la_energia.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download


      .subt.mb-4
        .row.align-items-center
          .col-md-auto.col-2
            img(src='@/assets/curso/temas/t1/subt.svg', alt='')
          .col-md-auto.col-10.ps-0
            h3.mb-0.text-white Características

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-5.col-md-10.mb-3.mb-lg-0(data-aos="fade-right")
          img(src='@/assets/curso/temas/t1/2.png', alt='')
        .col-lg-7(data-aos="fade-left")
          p La electricidad es una forma de energía que presenta dos ventajas fundamentales frente a otras fuentes:
          .row.justify-content-center.align-items-center
            .col-lg-2.col-md-2.d-none.d-md-block
              img(src='@/assets/curso/temas/t1/3.svg', alt='')
            .col-lg-10.col-md-10
              ul.lista-ul--color.sec2.fa-lista.mb-0
                li
                  i.fas.fa-circle-check
                  span.mb-0 Fácil transporte con mínimas pérdidas.
                li
                  i.fas.fa-circle-check
                  span.mb-0 Alta capacidad de transformación en otras formas de energía, como calor, luz o movimiento, y viceversa.


      .subt.mb-4
        .row.align-items-center
          .col-md-auto.col-3
            img(src='@/assets/curso/temas/t1/subt.svg', alt='')
          .col-md-auto.col-9.ps-0
            h3.mb-0.text-white Tipos de electricidad

      .tarjeta--container.row.mb-5(data-aos="fade-down")
        .col-md.tarjeta.color-primario.p-5
          .row.align-items-end.mb-4
            .col-5
              img(src='@/assets/curso/temas/t1/tarj1-1.jpg', alt='')
            .col-7
              h2.mb-0.bg-color-acento-contenido.text-white.w-fit.px-1 Electricidad estática
          p.text-white La electricidad estática estudia los fenómenos que se producen por la acumulación de cargas eléctricas en reposo. Esta se genera cuando los electrones se acumulan en la superficie de un cuerpo y se descargan al contacto con otro material conductor, lo que puede provocar una chispa o sensación de calambre.
          p.text-white.mb-0 Charles Coulomb fue quien describió las leyes de atracción y repulsión entre cargas eléctricas, estableciendo las bases del estudio de la electricidad estática. (Polanco Cáceres, 2010).
        .col-md.tarjeta.bg7.p-5
          .row.align-items-end.mb-4
            .col-5
              img(src='@/assets/curso/temas/t1/tarj1-2.jpg', alt='')
            .col-7
              h2.mb-0.bg-color-acento-contenido.text-white.w-fit.px-1 Electricidad dinámica
          p La electricidad dinámica se refiere al flujo continuo de cargas eléctricas a través de un conductor. Es la forma de electricidad que se utiliza habitualmente en sistemas eléctricos, como pilas, baterías y redes eléctricas.
          p.mb-0 Este tipo de electricidad se emplea para alimentar dispositivos eléctricos mediante circuitos cerrados.
          p.mb-0 Ejemplos comunes incluyen pilas para radios o linternas y baterías en vehículos. (Polanco Cáceres, 2010).

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-3.d-none.d-lg-block(data-aos="fade-right")
          img(src='@/assets/curso/temas/t1/4.jpg', alt='')
        .col-lg-9(data-aos="fade-left")
          .tarjeta.bg6.p-3.mb-5(data-aos="fade-down")
            .row.justify-content-around.align-items-center
              .col-3.col-sm-2.col-lg-2
                img.px-lg-2.m-auto(src="@/assets/curso/temas/t5/cta.png")
              .col.texto-blanco
                h4.mb-1 Para ampliar esta información diríjase a los siguientes enlaces donde encontrará información clave sobre:
                .row.justify-content-between.align-items-center.mb-3
                  .col.mb-3.mb-sm-0
                    p.mb-0.pe-lg-3 Electrotecnia
                  .col-sm-auto
                    a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Electrotecnia.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download
                .row.justify-content-between.align-items-center.mb-3
                  .col.mb-3.mb-sm-0
                    p.mb-0.pe-lg-3 Electrotecnia General
                  .col-sm-auto
                    a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Electrotrecnia_General.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download
                .row.justify-content-between.align-items-center.mb-3
                  .col.mb-3.mb-sm-0
                    p.mb-0.pe-lg-3 Fundamentos de circuitos eléctricos
                  .col-sm-auto
                    a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Fundamentos_de_circuito_electricos.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download
                .row.justify-content-between.align-items-center.mb-3
                  .col.mb-3.mb-sm-0
                    p.mb-0.pe-lg-3 Eficiencia energética en transformadores eléctricos
                  .col-sm-auto
                    a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Eficiencia_energetica_en_transformadores_electricos.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0
                    p.mb-0.pe-lg-3 Oferta y demanda de energía: tendencias y perspectivas
                  .col-sm-auto
                    a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Oferta_y_demanda_de_energia.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download


      .subt.mb-4
        .row.align-items-center
          .col-md-auto.col-3
            img(src='@/assets/curso/temas/t1/subt2.svg', alt='')
          .col-md-auto.col-9.ps-0
            h3.mb-0.text-white Energía eléctrica
      
      p.mb-5 La energía eléctrica es el resultado del movimiento de electrones a través de un conductor, provocado por una diferencia de potencial. Cuando se acciona un interruptor, se activa un flujo de millones de electrones, lo que permite el funcionamiento de aparatos eléctricos como televisores, lavadoras o motores.

      .row.justify-content-center.mb-5
        .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
          .subt2.mb-4
            h3.mb-0.py-1.px-4 Transformación de la energía
          p De acuerdo con el principio físico de conservación de la energía: “La energía no se crea ni se destruye, solo se transforma”.
          p La energía eléctrica puede convertirse en:
          ul.lista-ul--color.sec2.fa-lista.mb-0
            li
              i.fas.fa-circle-check
              span.mb-0 Luz (bombillas).
            li
              i.fas.fa-circle-check
              span.mb-0 Calor (resistencias).
            li
              i.fas.fa-circle-check
              span.mb-0 Movimiento (motores).
            li
              i.fas.fa-circle-check
              span.mb-0 Frío (refrigeración).
            li
              i.fas.fa-circle-check
              span.mb-0 Otras formas de trabajo útil.
        .col-lg-6(data-aos="fade-left")
          .subt2.mb-4
            h3.mb-0.py-1.px-4 Unidad de medida
          p.mb-4 La unidad empleada para medir la energía eléctrica es el kilovatio hora (kWh), que representa el trabajo realizado por una máquina de potencia 1 kilovatio durante una hora.  
          .bg-grad1.borde1.p-4
            p.form-big.mb-0.text-center 1 kWh = 3,6 × 10⁶ julios (J)


      .subt2.mb-4(data-aos="fade")
        h3.mb-0.py-1.px-4 Clasificación de las fuentes de energía

      p Según su disponibilidad y sostenibilidad, las fuentes de energía se clasifican en:

      TabsC.color-primario.mb-5(data-aos='fade-down')
        .py-3.py-md-4.py-lg-5.bg3(titulo="Energías renovables")
          .row.justify-content-center
            .col-11
              p.mb-4 Las energías renovables son aquellas que provienen de fuentes naturales capaces de regenerarse de forma continua. No se agotan con el uso y generan un bajo impacto ambiental, por lo que son consideradas una alternativa sostenible frente a las fuentes convencionales de energía.
              .row.justify-content-center.mb-5
                .col-lg-5.mb-4.mb-lg-0
                  p Ejemplos de energías renovables:
                  ul.lista-ul--color.sec2.fa-lista.mb-0
                    li
                      i.fas.fa-circle-check
                      span.mb-0 Energía de la biomasa.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 Energía solar térmica.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 Energía solar fotovoltaica.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 Energía hidráulica (hidroeléctrica).
                    li
                      i.fas.fa-circle-check
                      span.mb-0 Energía eólica.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 Energía geotérmica.
                .col-lg-7
                  img(src='@/assets/curso/temas/t1/tab1.png', alt='')
        .py-3.py-md-4.py-lg-5.bg3(titulo="Energías no renovables")
          .row.justify-content-center
            .col-11
              p.mb-4 Las energías no renovables provienen de recursos naturales limitados que no se regeneran a corto plazo, o cuya velocidad de formación es extremadamente lenta en comparación con su tasa de consumo. Su explotación produce un alto impacto ambiental, incluyendo contaminación del aire, agua y suelo, así como emisiones de gases de efecto invernadero.
              .row.justify-content-center.mb-5
                .col-lg-5.mb-4.mb-lg-0
                  p Ejemplos de energías no renovables:
                  ul.lista-ul--color.sec2.fa-lista.mb-0
                    li
                      i.fas.fa-circle-check
                      span.mb-0 #[b Carbón:] combustible fósil utilizado principalmente en plantas termoeléctricas.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 #[b Petróleo:] fuente principal de combustibles como la gasolina, diésel y queroseno.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 #[b Gas natural:] hidrocarburo utilizado para generación eléctrica, calefacción y cocina.
                    li
                      i.fas.fa-circle-check
                      span.mb-0 #[b Energía nuclear:] aunque no emite CO₂, se considera no renovable por depender del uranio, un mineral limitado, y por generar residuos radiactivos.
                .col-lg-7
                  img(src='@/assets/curso/temas/t1/tab2.png', alt='')

      
      .subt2.mb-4(data-aos="fade")
        h3.mb-0.py-1.px-4 Ramas de la electricidad 

      p.mb-5 La electricidad se divide en dos ramas circuito serie y circuito paralelo, por tal razón ampliaremos cada una:

      h4.mb-4(data-aos="fade") Circuito en serie

      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4(data-aos="fade-down")
        .bloque-texto-g__img(
          :style="{'background-image':`url(${require('@/assets/curso/temas/t1/5.jpg')})`}")
        .bloque-texto-g__texto.p-4.py-lg-5
          p Es aquel en el que varios elementos (como resistencias o cargas eléctricas) están conectados uno tras otro, es decir, de extremo a extremo, formando un único camino para la corriente eléctrica. Esto significa que la misma corriente eléctrica fluye a través de todos los componentes del circuito.
          br
          br
          p.mb-0 Según el principio de conservación de la energía, el voltaje total de la fuente de alimentación (fuerza electromotriz) se distribuye entre los distintos elementos conectados en serie.

      .row.justify-content-center.mb-4
        .col-lg-4.d-none.d-lg-block(data-aos="fade-right")
          img(src='@/assets/curso/temas/t1/9.png', alt='')
        .col-lg-8.text-center(data-aos="fade-left")
          .tarjeta.bg4.p-4.px-lg-5.mb-4
            h5 Es decir, la suma de los voltajes en cada resistencia es igual al voltaje total suministrado por la fuente:
            h5.mb-0 V total = V1 + V2 + V3 + … + Vn
          p.text-center Cada caída de voltaje en una resistencia depende del valor de la resistencia y de la corriente, según la Ley de Ohm.
          p.text-center La resistencia total de un circuito en serie se calcula sumando los valores individuales de cada resistencia:
          .row.justify-content-center.mb-4
            .col-lg-6.text-center
              img(src='@/assets/curso/temas/t1/6.svg', alt='')

          .row.justify-content-center.mb-4
            .col-lg-6.col-md-6.col-9.text-center
              .tarjeta.bg4.p-4.px-lg-5
                h5.mb-0 R total = R1 + R2 + R3 + … + Rn

      .row.justify-content-center.mb-5
        .col-lg-8(data-aos="fade-right")
          p Esto quiere decir que, al aumentar el número de resistencias en serie, también aumenta la resistencia total del circuito.
          p.mb-4 #[b Comportamiento de generadores en serie:] cuando se conectan generadores (fuentes de voltaje) en serie, se pueden sumar sus voltajes para obtener una mayor tensión total, siempre que tengan la misma polaridad.
          .tarjeta.bg4.p-4.px-lg-5.mb-4.text-center
            h5 La fórmula general para el voltaje total de generadores en serie es:
            h5.mb-0 E total = E1 + E2 + E3 + … + En
          p Es importante tener en cuenta que, si las polaridades no coinciden, habrá una resta de voltajes según cómo estén conectadas.
        .col-lg-4.col-md-8(data-aos="fade-left")
          .titulo-sexto.color-acento-contenido
            h5 Figura 1.
            span Circuito en serie
          figure.mb-2
            img(src='@/assets/curso/temas/t1/fig1.svg', alt='Representa un circuito eléctrico sencillo que incluye dos resistencias en serie (R1 y R2) y una fuente de corriente.')  
          figcaption Fuente: Alexander & Sadiku, (2013)
      

      h4.mb-4 Circuito en paralelo

      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-4(data-aos="fade-down")
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/t1/7.jpg')})`}")
        .bloque-texto-g__texto.p-4.py-lg-5      
          p A diferencia del circuito en serie, en el circuito en paralelo los elementos (como resistencias, bombillos u otros dispositivos eléctricos) se conectan de forma que todos comparten los mismos dos puntos de conexión. Esto significa que cada uno de ellos recibe la misma tensión (voltaje), aunque la corriente que circula por cada uno puede ser diferente, dependiendo de su resistencia.
          br
          br
          p.mb-0 Como lo señala Hermosa Donate (2003), en un circuito en serie la corriente es la misma en todos los elementos, mientras que, en un circuito en paralelo, lo que se mantiene constante es la tensión aplicada a cada componente.

      .row.bgc-3.align-items-center.p-2.p-md-3.mb-5(data-aos="fade-down")
        .col-lg-12.col-12.px-lg-4
          .row.justify-content-center.align-items-center

            .row.justify-content-center
              .col-lg-12
                .titulo-sexto.color-acento-contenido
                  h5 Figura 2.
                  span Circuito en paralelo
              .col-lg-4.col-md-5
                figure.mb-2
                  img(src='@/assets/curso/temas/t1/fig2.svg', alt='La figura representa un circuito paralelo compuesto por dos resistencias, R1 y R2, conectadas entre dos nodos comunes. La fuente de alimentación tiene un voltaje de 12V entre los puntos A y el terminal de referencia (0V). La corriente total se divide en dos ramas: I1 atraviesa R1 e I2 atraviesa R2, cumpliendo la Ley de nodos de Kirchhoff, donde la corriente que entra al nodo A es igual a la suma de las corrientes que salen por cada rama.')  
                figcaption Fuente: Alexander & Sadiku, (2013)

      p.text-center En los circuitos en paralelo:

      .row.justify-content-center.mb-5(data-aos="fade-down")
        .col-lg-4.col-md-6.mb-3
          .tarjeta.tarj-hover.text-center.p-4.h-100
            img.mb-0(src='@/assets/curso/temas/t1/tarj2-1.png', alt='')
            p.mb-0 El voltaje en cada rama del circuito es igual al voltaje de la fuente.
        .col-lg-4.col-md-6.mb-3
          .tarjeta.tarj-hover.text-center.p-4.h-100
            img.mb-0(src='@/assets/curso/temas/t1/tarj2-2.png', alt='')
            p.mb-0 La corriente total del circuito es la suma de las corrientes que pasan por cada rama.
        .col-lg-4.col-md-6.mb-3
          .tarjeta.tarj-hover.text-center.p-4.h-100
            img.mb-0(src='@/assets/curso/temas/t1/tarj2-3.png', alt='')
            p.mb-0 La resistencia total equivalente disminuye al agregar más dispositivos, porque se abren más caminos para que circule la corriente.

      .row.justify-content-center.mb-5
        .col-lg-9(data-aos="fade-right")
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tipo-a bg8")
            .row.justify-content-center(titulo="Para generadores")
              .col-md-10
                p.mb-0 VT = V1 = V2 = ⋯ Vn
                p Donde VT = Voltaje total, V1 = Voltaje 1, V2 = Voltaje 2, Vn = Voltaje n.
                p.mb-0 IT = I1 + I2 + ⋯ + In
                p IT = Intensidad total, I1 = Intensidad 1, I2 = Intensidad 2, In = Intensidad n.
            .row.justify-content-center(titulo="Para resistencias")
              .col-md-10
                p 1/RT = 1/R1 + 1/R2 + ⋯ 1/(RT)  
                p Donde RT = Resistencia total, R1 = Resistencia 1, R2 = Resistencia 2.
            .row.justify-content-center(titulo="Para condensadores")
              .col-md-10
                p CT = C1 + C2 + ⋯ + Cn
                p Donde CT = Capacitancia total, C1 = Capacitancia 1, C2 = Capacitancia 2, Cn = Capacitancia n.
        .col-lg-3.d-none.d-lg-block(data-aos="fade-left")
          img(src='@/assets/curso/temas/t1/8.jpg', alt='')

      h4.mb-4(data-aos="fade") Para interruptores:

      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        h5 Tabla 1.
        span Tabla de Interruptores

      .row.justify-content-center.mb-5(data-aos='fade-down')
        .col-lg-9
          .tabla-a.color-acento-contenido
            table
              caption Referencia Tabla - Alexander & Sadiku, (2013)
              thead.text-white
                tr.bg-color-acento-contenido
                  th Interruptor 1
                  th Interruptor 2
                  th Salida
              tbody
                tr.bg9
                  td Abierto
                  td Abierto
                  td Abierto
                tr
                  td Abierto
                  td Cerrado
                  td Cerrado
                tr.bg9
                  td Cerrado
                  td Abierto
                  td Cerrado
                tr
                  td Cerrado
                  td Cerrado
                  td Cerrado

          


      .subt.mb-4(data-aos="fade-right")
        .row.align-items-center
          .col-md-auto.col-3
            img(src='@/assets/curso/temas/t1/subt3.svg', alt='')
          .col-md-auto.col-9.ps-0
            h3.mb-0.text-white Circuito mixto

      p Es aquel que combina elementos conectados tanto en serie como en paralelo. Para resolver problemas asociados a este tipo de circuitos, se recomienda simplificar las conexiones paso a paso, sumado a esto cuando se identifican dos elementos conectados en paralelo y dispuestos consecutivamente, pueden ser reemplazados por un equivalente en serie. Esta estrategia permite una solución más sencilla y ordenada del circuito (Hermosa Donate, 2003).

      .row.bgc-3.align-items-center.p-2.p-md-3.mb-5(data-aos="fade-down")
        .col-lg-12.col-12.px-lg-4
          .row.justify-content-center.align-items-center

            .row.justify-content-center
              .col-lg-12
                .titulo-sexto.color-acento-contenido
                  h5 Figura 3.
                  span Circuito mixto
              .col-lg-6.col-md-8
                figure.mb-2
                  img(src='@/assets/curso/temas/t1/fig3.svg', alt='La figura representa un circuito mixto compuesto por una combinación de resistencias en serie y en paralelo. La fuente de voltaje V alimenta el sistema. Las resistencias R1 y R5 están conectadas en serie; a partir de allí, la corriente se divide en varias ramas: una con R2 y R3 en paralelo, otra con R4, y otra que continúa el trayecto de la corriente total. Las corrientes I1, I2, I3, I4 e I5 indican el flujo a través de diferentes secciones del circuito. Este tipo de configuración permite analizar el comportamiento combinado de las leyes de Kirchhoff en serie y paralelo.')  
                figcaption Fuente: Alexander & Sadiku, (2013)




  </template>

<script>
export default {
  name: 'Tema1',
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
