<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.cs
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Métodos de métricas e indicadores de monitoreo

    .row.align-items-center.justify-content-center.mb-5
      .col-7.col-lg-5(data-aos="fade-left")
          img(src='@/assets/curso/images/tema1/img_1.png'  alt='').mb-3
      .col-lg-7(data-aos="fade-right")
        p.mb-3 Se mide la seguridad fundamentalmente, para entenderla.  Lo ideal es establecer programas de métricas de seguridad que vayan más allá de la recopilación de datos y estén orientados realmente a la medición.
          .jumbotron.p-4
            p.mb-0 La recopilación de datos de seguridad es fundamental para cualquier programa de métricas eficaz, pero sin un contexto para esos datos y una idea de por qué se recopilan y qué se pretende hacer con ellos, podría verse limitado a describir la medición solo en términos de terabytes de datos de registro y el volumen de estanterías que ocupan los informes de los auditores.

    p.mb-3 A continuación se pueden observar algunas consideraciones a la hora de emprender un programa de métricas de seguridad:

    .row.justify-content-center.align-items-star.mb-2.mb-lg-5
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in-down")
          .row.justify-content-center.align-items-center(titulo="Las métricas son un viaje, no el destino")
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 Una vez establecido un programa de métricas de seguridad, preguntarse cómo los resultados han mejorado la comprensión de los sistemas y procesos de seguridad.

          .row.justify-content-center.align-items-center(titulo="Comprender no es diagnosticar")
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 Conocer el porcentaje de contraseñas fáciles de descifrar o la proporción de computadores vulnerables no es suficiente si dicha información no permite mejorar la eficacia de la seguridad computacional. Incluso si la seguridad ha mejorado, pero sin saber a qué obedece la mejora, algo le falta al programa de métricas de seguridad.

          .row.justify-content-center.align-items-center(titulo="Las métricas no son conocimiento")
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 Las métricas son depósitos de datos conceptuales que definen y estandarizan información.  Al igual que las entradas de palabras bien definidas no transforman un diccionario en literatura: ¡Solo las personas pueden lograr estas cosas!


      .col-8.col-lg-4(data-aos="fade-right").d-none.d-lg-block
          img(src='@/assets/curso/images/tema1/img_2.svg'  alt='')

    .row.justify-content-center.align-items-star
      .col-8.col-lg-4(data-aos="fade-left").d-none.d-lg-block
          img(src='@/assets/curso/images/tema1/img_3.svg'  alt='').mb-3
      .col-lg-8(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in-down")
          .row.justify-content-center.align-items-center(titulo="No es cuestión de recopilar muchos datos")
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 Un pequeño conjunto de datos, bien entendido y aplicado regularmente, es mucho más valioso que una montaña de datos sin utilizar.
          .row.justify-content-center.align-items-center(titulo="La medición es una actividad")
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 La medición implica realizar observaciones y recopilar datos para obtener una visión práctica de lo que se intenta comprender. La distinción es importante, porque las métricas no solo aportan información sobre la seguridad informática, sino también sobre los costes y los riesgos.

          .row.justify-content-center.align-items-center(titulo="Analizar y actuar")
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 La medición sin análisis y acción supone una pérdida de tiempo y dinero y contribuye a la incertidumbre y al riesgo en lugar de reducirlos. Conocer el problema y no actuar en consecuencia, lleva a una violación de la seguridad, que podría terminar siendo más perjudicial que la ignorancia que existía antes de que se recogieran los datos.

    Separador

    #t_1_1.titulo-segundo.color-acento-contenido
      .h2 1.1  Características

    p.mb-5 Dadas sus limitaciones, algunas métricas pueden convertirse en indicadores engañosos de la eficacia de la seguridad.  Hay muchos argumentos sobre lo que hace que una métrica sea buena o mala:

    .row.my-4.align-items-lg-stretch
      .col-xl-4.mb-3
        .bg-c1.p-4
          .row
            .col-auto
              img(src='@/assets/curso/images/tema1/ico_1.svg'  alt='', style="max-width:92px").m-auto
            .col
              p.mb-0 Cualquier medida empírica que ayude a una organización a reducir la incertidumbre es una buena métrica.

      .col-xl-4.mb-3
        .bg-c1.p-4
          .row
            .col-auto
              img(src='@/assets/curso/images/tema1/ico_1.svg'  alt='', style="max-width:92px").m-auto
            .col
              p.mb-0 Una métrica que deba descartarse simplemente porque no sea cuantitativa o específica.

      .col-xl-4.mb-3
        .bg-c1.p-4
          .row
            .col-auto
              img(src='@/assets/curso/images/tema1/ico_1.svg'  alt='', style="max-width:92px").m-auto
            .col
              p.mb-0 Una métrica es buena simplemente porque sea fácil e inequívoca.


    p.mb-3 Cualquier medición se vuelve problemática cuando se realiza de forma deficiente y cuando quienes miden no son suficientemente críticos con sus propios métodos. Los problemas que pueden surgir de los intentos poco sofisticados de medir la seguridad pueden incluir cuestiones de calidad de los datos, rigor empírico o el hecho de que las métricas se utilicen de forma inmadura o engañosa.

    .bg-c2.my-5
      .p-5
        p.mb-4 De todos los fenómenos que preocupan en el ámbito de la seguridad informática, el riesgo parece ser el primero de la lista. Pero, pese a su importancia, a menudo es uno de los conceptos menos comprendidos. Una matriz de riesgos de seguridad basada en juicios de expertos puede ser una estimación útil, pero sigue siendo un conjunto de opiniones sobre el riesgo. Los mayores problemas de seguridad identificados en la matriz no son necesariamente los mayores problemas de seguridad a los que se enfrenta la empresa. La esperanza es que los verdaderos riesgos de seguridad se correlacionen de alguna manera con las opiniones de los expertos responsables de la seguridad.

        .row.justify-content-center.align-items-center
          .col-xl-6
            img(src='@/assets/curso/images/tema1/fig_1.svg')



    .row.align-items-start.justify-content-center.mb-5
      .col-xl-7(data-aos="fade-left")
        p.mb-3 El punto no es que la matriz de riesgos de seguridad sea un mal método de medición, sino pretender que la matriz mida el riesgo real. Desgraciadamente, la mayoría de los usuarios de la matriz en la seguridad informática la utilizan para tomar decisiones "basadas en el riesgo".

        p.mb-0 La matriz de riesgos se ha convertido en el motor de algunas de las metodologías de evaluación de riesgos de seguridad más comunes hoy en día, utilizadas como metodología formal de evaluación y gestión de riesgos de la organización, como exigen algunos marcos de cumplimiento. En estos casos, la matriz no actúa como un prototipo inicial de medición de riesgos que conduce a más preguntas y métricas, sino como el resultado final del proceso de evaluación de riesgos. El asunto no es abandonar la matriz de riesgos como medio de apoyo a las decisiones de seguridad, pero sí utilizarla para fines diferentes a los acostumbrados, como se puede ver a continuación:
      .col-xl-5.d-none.d-xl-block
          img(src='@/assets/curso/images/tema1/img_4.png'  alt='')

    .tarjeta.bg-c3.px-4.pt-4.pb-5
      .row.justify-content-center.align-items-center
        .col-md-11
          SlyderA(tipo="b")
            .row.justify-content-center.align-items-center
              .col-md-12.col-xl-6.mb-4.mb-xl-0
                h3.mb-3 Utilizar la matriz para crear un prototipo de nuevas evaluaciones de riesgos
                p.mb-3 Ante los resultados, plantearse ¿por qué?, pensando en preguntas de seguimiento que conducen a nuevas mediciones:
                ul.lista-ul--color.mt-3.mb-0
                  li
                    i.vineta(data-aos="fade-up")
                    span ¿Por qué es tan probable que el sistema se vea comprometido?
                  li
                    i.vineta(data-aos="fade-up")
                    span ¿Por qué el impacto es tan grave en comparación con otros sistemas?

              .col-md-12.col-xl-6
                figure
                  img(src='@/assets/curso/images/tema1/img_5.png', style="max-width: 505px",  alt='')(data-aos="zoom-in").m-auto

            .row.justify-content-center.align-items-center
              .col-md-12.col-xl-6.mb-3.mb-xl-0
                h3.mb-3 Medir las diferencias de acuerdo.
                p.mb-3 Comparar lo que piensan las diferentes personas de la organización sobre el riesgo, identificando las áreas en las que hay acuerdo o aquellas en las que hay amplia variación en las opiniones.

                p.mb-0 Este análisis permite descubrir dónde debe concentrar la organización sus esfuerzos de evaluación de riesgos, incluyendo dónde realizar actividades de medición más sofisticadas y sólidas.
              .col-md-12.col-xl-6
                figure
                  img.mt-5(src='@/assets/curso/images/tema1/img_6.png', style="max-width: 505px",  alt='')(data-aos="zoom-in").m-auto


    Separador

    #t_1_2.titulo-segundo.color-acento-contenido
      .h2 1.2  Tipos


    .bg-c4.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-md-11
          .row.align-items-center.justify-content-center
            .col-xl-4(data-aos="fade-left").d-none.d-xl-block
              figure.p-3
                img(src='@/assets/curso/images/tema1/img_7.svg'  alt='').mb-3

            .col-xl-8(data-aos="fade-right")
              p.mb-3 Los datos que se recogen con más frecuencia para entender la seguridad de la información tienen que ver con las vulnerabilidades del sistema y los esfuerzos para comprometerlas.

              p.mb-3 Las estadísticas de vulnerabilidad del sistema se producen cuando una organización ejecuta un escáner de seguridad en su red, se identifican nuevos #[em exploits] y se dan a conocer a los proveedores y al público, y cuando las organizaciones publican los informes resultantes de las encuestas de la industria que han realizado o los análisis de los datos de seguridad que han recogido.

              p.mb-0 Las estadísticas de incidentes proceden de los registros del sistema, de los sistemas de detección y prevención de intrusiones y de las encuestas y análisis del sector. Estas cifras suelen utilizarse como indicadores generales del estado actual de la seguridad informática.


    .row.justify-content-center.align-items-center.mb-5
      .col-auto.me-4.d-none.d-lg-flex
        figure
          img(src="@/assets/curso/images/tema1/ico_3.svg", alt="alt")
      .col-lg
        p Las métricas de seguridad que se utilizan hoy en día son insuficientes para el futuro de la seguridad de la información. Es preciso desarrollar enfoques más sofisticados de los procesos de seguridad en general y de la medición y evaluación de esos procesos en particular. Las experiencias de otros sectores como los seguros, la fabricación y el diseño, que se han enfrentado a los mismos retos, ofrecen valiosas lecciones sobre cómo pensar los datos, los procesos y las personas a la hora de abordar la generación de métricas de seguridad.

        p Observe el siguiente video e identifique aspectos clave en la definición de un programa de métricas de seguridad:

    figure
      .video
        <iframe width="560" height="315" src="https://www.youtube.com/embed/YkvjTcaOtac" title="Reevaluando las métricas de seguridad" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      figcaption Video. Reevaluando las métricas de seguridad.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
