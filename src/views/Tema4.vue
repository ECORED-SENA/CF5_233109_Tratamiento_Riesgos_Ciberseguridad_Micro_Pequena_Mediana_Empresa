<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.cs
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Fundamentos de SOC - <i>Security Operation Center</i>

    p.mb-5 El centro de operaciones de seguridad, más comúnmente llamado "el SOC", es una unidad centralizada que se ocupa de los problemas de seguridad tanto a nivel organizativo como técnico. Esto ocurre mediante el uso de personas, procesos y capacidades para prestar servicios que pueden incluir:

    .row.justify-content-center(data-aos="zoom-in")
      .col-10.col-lg-6.col-xl-4.mb-3(data-aos="fade-right")
        .jumbotron-2.p-2.px-3.mb-3.h-100
          .row.justify-content-center.align-items-center.mt-2
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_1.svg'  alt='', style="width:80px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 <b>Identificación y la reducción de riesgos.</b>

      .col-10.col-lg-6.col-xl-4.mb-3(data-aos="fade-right")
        .jumbotron-2.p-2.px-3.mb-3.h-100
          .row.justify-content-center.align-items-center.mt-2
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_2.svg' alt='', style="width:80px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 <b>Tratamiento de vulnerabilidades.</b>

      .col-10.col-lg-6.col-xl-4.mb-3(data-aos="fade-right")
        .jumbotron-2.p-2.px-3.mb-3.h-100
          .row.justify-content-center.align-items-center.mt-2
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_3.svg' alt='', style="width:80px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 <b>Adhesión a los requisitos de cumplimiento.</b>

    .row.justify-content-center
      .col-10.col-lg-6.col-xl-4.mb-3(data-aos="fade-right")
        .jumbotron-2.p-2.px-3.mb-3.h-100
          .row.justify-content-center.align-items-center.mt-2
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_4.svg'  alt='', style="width:80px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 <b>Respuesta a los incidentes.</b>

      .col-10.col-lg-6.col-xl-4.mb-3(data-aos="fade-right")
        .jumbotron-2.p-2.px-3.mb-3.h-100
          .row.justify-content-center.align-items-center.mt-2
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_5.svg' alt='', style="width:80px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 <b>Recogida de pruebas forenses.</b>

    p.my-5 A continuación, se detallan algunos conceptos y elementos generales de las etapas de operación de un SOC, que favorecen un correcto funcionamiento:

    .row.justify-content-center.align-items-star.mb-5
      .col-xl-4(data-aos="fade-right").d-none.d-xl-block
          img(src='@/assets/curso/images/tema4/img_1.svg'  alt='')
      .col-xl-8(data-aos="fade-left")
        .p-xl-5.p-2
          LineaTiempoD.color-secundario.especial
            .row(titulo='Prevención' numero='1')
              .col-md-12.col-lg-12.mb-4.mb-md-0
                p.mb-0 Con base en la experiencia y adopción de buenas prácticas de ciberseguridad, el SOC debe apropiar medidas de prevención a nivel técnico y de conciencia en la organización. Entre las soluciones preventivas se pueden considerar aplicación de controles de seguridad (#[em firewalls, antimalware], etc.), el monitoreo continuo de la seguridad, el análisis y gestión de las vulnerabilidades técnicas.
            .row(titulo='Detección' numero='2')
              .col-md-12.col-lg-12.mb-4.mb-md-0
                p.mb-0 Consiste en el monitoreo constante de los eventos para detectar amenazas, vulnerabilidades, intrusiones y fallos de seguridad, para responder de manera rápida y eficaz. La principal herramienta que apoya esta etapa son las SIEM.
            .row(titulo='Análisis' numero='3')
              .col-md-12.col-lg-12.mb-4.mb-md-0
                p.mb-0 En esta etapa se deben analizar los eventos detectados para determinar si corresponden a amenazas reales o si son falsas alertas. Los sistemas SIEM ayudan en el proceso de análisis con su base de datos de conocimientos y experiencias anómalas, registradas previamente, así como en la configuración de las reglas de cumplimiento.
            .row(titulo='Respuesta' numero='4')
              .col-md-12.col-lg-12.mb-4.mb-md-0
                p.mb-0 Consiste en las acciones que se toman para responder frente a un evento o incidentes de ciberseguridad; las mismas deben estar planificadas de manera que se apliquen las medidas o controles de forma eficaz.

    Separador

    #t_4_1.titulo-segundo.color-acento-contenido
      .h2 4.1  Objetivos


    .row.justify-content-center.align-items-star.mb-5
      .col-lg-8(data-aos="fade-right")
        .bloque-texto-c.color-custom-5.p-4
          i.fas.fa-quote-right
          h4.mb-2 El objetivo de un SOC es detectar, analizar y corregir incidentes de ciberseguridad utilizando soluciones tecnológicas y enfoques diferentes. Estos supervisan y analizan la actividad en redes, servidores, terminales, bases de datos, aplicaciones, sitios web y otros sistemas, en busca de señales débiles o comportamientos anormales que puedan indicar un incidente de seguridad o un compromiso.
          span (Oracle.com, 2021).
      .col-10.col-lg-4.col-sm-8(data-aos="fade-left").d-none.d-lg-block
          img.mt-3(src='@/assets/curso/images/tema4/img_2.svg'  alt='')

    .row.align-items-center.justify-content-center.fondo-4.mb-5.p-4
      .col-xl-4.col-lg-8.col-sm-6.col-8(data-aos="fade-left")
        img(src='@/assets/curso/images/tema4/img_3.svg'  alt='').mb-3
      .col-xl-6(data-aos="fade-right")
        p.mb-3 Los objetivos de un centro de operaciones de seguridad (SOC), deben enfocarse en:
          ul.lista-ul--color.mt-4
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Reducir riesgos y tiempo de indisponibilidad de aplicaciones y servicios.
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Control y prevención de amenazas.
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Disminuir la carga de trabajo administrativa del personal de seguridad.
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Establecer el personal de seguridad y definir responsabilidades.
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Indicar los tiempos de soporte y escalamiento de eventos.
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Definir los procesos de auditoría y soportes de cumplimiento.
            li
              i.vineta-2(data-aos="fade-up")
              span.ps-2 Responder a incidentes y recuperación.

    Separador

    #t_4_2.titulo-segundo.color-acento-contenido
      .h2 4.2  Alcance

    p.mb-3 Los SOC maduros de todo el mundo suelen tener en común un conjunto básico de servicios de seguridad que pueden ser internos, subcontratados o incluso bajo demanda, lo que permite al SOC disponer de los servicios deseados cuando los necesite. Independientemente del enfoque de prestación, hay servicios que todo SOC debe ofrecer. Para resumir esos servicios comunes del SOC, se pueden definir las siguientes ofertas:

    .row.justify-content-center.align-items-star.mb-5
      .col-lg-10(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in-down")
          .row.justify-content-center.align-items-center(titulo="Gestión de riesgos")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_6.svg' alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Identificar y tomar decisiones para hacer frente a los riesgos de la organización. Desde la seguridad física de los activos hasta la corrección de las vulnerabilidades digitales que existen en el #[em software]. También aplica a la corrección de políticas deficientes y falta de educación en seguridad de los miembros de una organización.

          .row.justify-content-center.align-items-center(titulo="Gestión de la vulnerabilidad")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_7.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Identificar y gestionar el riesgo de las vulnerabilidades técnicas: detección de vulnerabilidades en el #[em software] que se encuentra en los servidores, los ordenadores portátiles y los dispositivos IoT. La mayoría de los SOC utilizan escáneres de vulnerabilidad e inteligencia de amenazas externa para identificar las vulnerabilidades.

          .row.justify-content-center.align-items-center(titulo="Gestión de incidentes")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_8.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Respuesta a eventos relacionados con seguridad: acciones como el aislamiento de los sistemas, la alerta a los miembros del equipo y la aplicación de medidas correctivas para resolver el problema. Tecnologías como las herramientas de orquestación, la inteligencia artificial y los #[em playbooks] se están haciendo muy populares para ayudar a los SOC en los servicios de respuesta a incidentes.

          .row.justify-content-center.align-items-center(titulo="Análisis")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_9.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Análisis de varios tipos de artefactos: identificación de características, ingeniería inversa, análisis de vulnerabilidad/explotación, análisis causa raíz, reparación y análisis de mitigación.  El análisis utiliza herramientas como IDA Pro para desmontar el #[em malware] y comprender su funcionamiento.


          .row.justify-content-center.align-items-center(titulo="Cumplimiento")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_10.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Evaluar y mantener los requisitos de cumplimiento de la organización: tanto los requisitos obligatorios por ley (HIPAA y PCI DSS), como los objetivos impulsados por la organización (norma NIST o ISO), que no son exigidos por la ley, pero que podrían ser considerados como una política requerida por la organización o sus clientes.

          .row.justify-content-center.align-items-center(titulo="Análisis forense digital")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_11.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Recopilación de pruebas tras el incidente para determinar la causa y preparar acciones legales. La ciencia forense digital se distingue de la respuesta a incidentes y el análisis, en el aspecto legal relativo a la forma en que se recogen las pruebas (si se manipula un archivo durante la investigación, se arruina cualquier posibilidad de utilizar esa prueba en un tribunal).

          .row.justify-content-center.align-items-center(titulo="Conciencia de la situación y de la seguridad")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_12.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Proporcionar a la organización conciencia de su entorno operativo y de las posibles amenazas. Incluye educación sobre elementos críticos que podrían afectar los objetivos de la organización, amenazas potenciales y acciones contra el riesgo operativo y las amenazas.

          .row.justify-content-center.align-items-center(titulo="Investigación y desarrollo")
            .col-auto
              img(src='@/assets/curso/images/tema4/ico_13.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Investigar el panorama de las amenazas en constante evolución, desarrollar nuevas herramientas y técnicas, y modificar las herramientas existentes para mejorar su eficacia.

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
