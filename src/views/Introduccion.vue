<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.align-items-center.justify-content-center.mb-5
      .col-lg-8(data-aos="fade-right")
        p.mb-3 En los últimos años se ha producido un creciente interés por las métricas de seguridad, varios libros, numerosos artículos e informes se han dedicado a demostrar las ventajas de medir la seguridad de computación. Las métricas de seguridad se han convertido en un tema candente tan rápidamente que algunos podrían suponer que se acaba de descubrir la posibilidad de medir lo que se hace. Pero esto no es exacto, métricas de seguridad como la esperanza de pérdida anualizada (ALE), el coste total de propiedad (TCO) y la evaluación de riesgos cuantitativa y cualitativa, han sido utilizadas por los profesionales de la seguridad durante años.
        p.mb-3 Lo que es nuevo en las métricas de seguridad es la creciente comprensión de que muchos de los esfuerzos tradicionales de medición son insatisfactorios, dado que no ofrecen la información que realmente se necesita para apoyar las decisiones y articular el valor de las actividades de seguridad. Tampoco son adecuados para el cambiante panorama de la seguridad, con amenazas más sutiles y una mayor responsabilidad y escrutinio. El consenso creciente es que se debe medir mejor y considerar formas nuevas e innovadoras de analizar los datos métricos que ya se tienen.
        p.mb-3 El presente componente formativo analiza algunos conceptos clave para la generación de métricas de seguridad desde la lógica del proceso de evaluación a la ciberseguridad de las organizaciones.  Se puede revisar el siguiente video de introducción a la temática:
      .col-7.col-lg-4(data-aos="fade-left")
        img(src='@/assets/curso/images/tema1/img_intro.jpg'  alt='')

    figure.mb-5
      .video
        <iframe width="560" height="315" src="https://www.youtube.com/embed/NGJBT7D2hpQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
