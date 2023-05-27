<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.cs
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero 
        span 3
      h1 Fundamentos de SIEM - <i>Security Information and Event Management</i>

    .row.align-items-center.justify-content-center.fondo-4.mb-5.p-4
      .col-10.col-lg-4.col-sm-8(data-aos="fade-left")
          img(src='@/assets/curso/images/tema3/img_1.svg'  alt='').mb-3
      .col-lg-6(data-aos="fade-right") 
        p.mb-3 El sistema de gestión de información y eventos de seguridad (SIEM) consiste en una compleja colección de tecnologías diseñadas para proporcionar visión y claridad sobre el sistema de tecnología de la información (TI) corporativo en su conjunto, beneficiando también a los analistas de seguridad y administradores de TI. 

        p.mb-0 Observar en el siguiente video algunas de las ventajas ofrecidas por el sistema de gestión de información y eventos de seguridad (SIEM).

    figure.mb-5
      .video
        <iframe width="560" height="315" src="https://www.youtube.com/embed/aTO98EWWtjk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    Separador

    #t_3_1.titulo-segundo
      .h2 3.1  Tipos

    p.mb-3 Ahora se debe revisar algunas consideraciones relacionadas con la tipología del sistema SIEM, partiendo de la gestión de registros, que implica las acciones descritas a continuación:

    .tarjeta.bg_grad-01.p-4.mb-5(data-aos="zoom-in-up")
      SlyderA(tipo="b")
        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Configuración de nodos
            p.mb-3 Envío de eventos relevantes del sistema y de las aplicaciones a una base de datos centralizada, gestionada por la aplicación SIEM.
            p.mb-3 SIEM analiza los datos y proporciona servicios de almacenamiento, organización, recuperación y archivo de registros.
            p.mb-0 Los nodos incluyen sistemas informáticos que ejecutan varios sistemas operativos (Linux, UNIX, Windows) y sistemas y dispositivos de infraestructura de red (routers, conmutadores gestionados, cortafuegos, servidores proxy, sistemas de detección de intrusiones (IDS), sistemas de acceso remoto).
           
          .col-12.col-lg-5(data-aos="fade-right") 
              img.mt-5(src='@/assets/curso/images/tema3/img_2.png'  alt='')

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Creación de filtros o reglas y temporizadores 
            p.mb-3 Para auditar y validar el cumplimiento o identificar las violaciones a los requisitos de cumplimiento impuestos a la organización. 
            p.mb-0 Las reglas podrían incluir: supervisión de la frecuencia de los cambios de contraseña, identificación de los parches del sistema operativo (SO) o de las aplicaciones que no se instalan, la frecuencia de auditoría de las actualizaciones del antivirus, el antispyware y el IDS.  


          .col-12.col-lg-5(data-aos="fade-right") 
              img.mt-5(src='@/assets/curso/images/tema3/img_3.svg'  alt='')          

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Correlación de eventos  
            p.mb-3 Enseña al sistema a considerar varias condiciones antes de activar la alarma. 
            p.mb-3 Por ejemplo, un servidor que funciona al 100% de utilización de la CPU podría responder a varias causas:  
            ul.lista-ul--color.mt-3
              li
                i.vineta-1(data-aos="fade-up")
                p.mb-0 Una aplicación fallida que ha bloqueado el servidor.
              li
                i.vineta-1(data-aos="fade-up")
                p.mb-0 Sobrecarga del sistema con actividad legítima indicando servicios o aplicaciones que deben ser distribuidos en servidores adicionales (cluster).
              li
                i.vineta-1(data-aos="fade-up")
                p.mb-0 Un gusano que ejecuta un ataque de denegación de servicio (DoS).  Actividad momentánea y natural del servidor.
  
          .col-12.col-lg-5(data-aos="fade-right") 
              img.mt-5(src='@/assets/curso/images/tema3/img_4.png'  alt='')        

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Respuesta activa
            p.mb-3 El SIEM toma automáticamente medidas correctivas ante las amenazas percibidas o las configuraciones erróneas, por ejemplo, añadiendo filtros de IP y de puertos en la lista de control de acceso (ACL) de un router o un cortafuegos. 
            p.mb-0 Aunque hay algunos beneficios obvios de las respuestas automatizadas, sólo en una instalación madura y en un SIEM finamente ajustado debería implementarse su utilización. De lo contrario, el sistema SIEM podría estar respondiendo a una colección de eventos falsos positivos, convirtiéndose en un arma de doble filo.
          .col-12.col-lg-5(data-aos="fade-right") 
              img.mt-5(src='@/assets/curso/images/tema3/img_5.png'  alt='') 

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Seguridad de los puntos finales
            p.mb-0 El sistema SIEM puede supervisar si el cortafuegos de un PC o servidor está funcionando e identificar cuándo se actualizaron por última vez las definiciones de AV o cuándo un nodo se infecta con spyware. Incluso puede gestionar la seguridad de los puntos finales, realizando mejoras en la seguridad del nodo en el sistema remoto, como la configuración de cortafuegos y la actualización y supervisión de productos AV, antispyware y antispam en los nodos del sistema. 

          .col-12.col-lg-5(data-aos="fade-right") 
              img.mt-5(src='@/assets/curso/images/tema3/img_6.png'  alt='') 


    Separador

    #t_3_2.titulo-segundo
      .h2 3.2  Características

    .row.align-items-center.justify-content-center.mb-5
      .col-12.col-lg-5.col-sm-8(data-aos="fade-left")
          img(src='@/assets/curso/images/tema3/img_7.jpg'  alt='').mb-3
      .col-lg-7(data-aos="fade-right") 
        p.mb-3 Implementar un sistema SIEM no es un asunto de poca monta económicamente hablando, por lo que es necesario justificar adecuadamente la propuesta.  Al proporcionar una visión más completa de las operaciones de TI y sobre la seguridad y protección de los activos valiosos de información dentro de organización, se espera que con un sistema SIEM en funcionamiento, la empresa experimente menos pérdidas, que, llevadas a costos, compensan el precio del SIEM:

        ul.lista-ul--color.mt-3
          li
            i.vineta(data-aos="fade-up")
            p.mb-0 En primer lugar, con un SIEM se automatizan muchas funciones de supervisión, alerta, análisis, correlación y elaboración de informes, de manera más eficiente que los sistemas propios, que se realizan muchas veces de forma manual.  
          li
            i.vineta(data-aos="fade-up")
            p.mb-0 En segundo lugar, el sistema SIEM ayuda a la organización a cumplir las directrices legales exigidas en materia de TI y seguridad, permitiendo identificar y corregir los sistemas y procesos que no cumplen la normativa y protegiéndola de multas relacionadas con el cumplimiento.

          li
            i.vineta(data-aos="fade-up")
            p.mb-0 Por último, y quizás lo más importante, de contar con el sistema SIEM es poder reducir drásticamente la superficie de ataque de una organización, lo que, combinado con las capacidades de reconocimiento, alerta y respuesta más rápidas proporcionadas por el SIEM, traerá beneficios al reducir la probabilidad de una violación de la seguridad y minimizar las pérdidas potenciales ocurridas durante una violación de la seguridad u otro tipo de evento de pérdida.

        
    Separador

    #t_3_3.titulo-segundo
      .h2 3.3  Aplicación

    .rectangle_03.mb-5(data-aos="zoom-in")
      .row.justify-content-center.align-items-center
        .col-auto.me-4.d-none.d-lg-flex
          figure
            img(src="@/assets/curso/images/tema3/ico_1.svg", alt="alt")
        .col-lg
          p.mb-3 Ante el aumento de sucesos de ciberdelincuencia, incidentes de robo de identidad y de propiedad intelectual y ciberataques, los profesionales de la seguridad deben velar por asegurar cada vez mejor su entorno, utilizando toda la información a disposición para determinar cómo desplegar los recursos de que dispone. 

          p.mb-0 Al abordar un nuevo entorno o reevaluar el actual, es primordial determinar la mejor estrategia de seguridad que dependerá en gran medida del modelo de negocio de la organización.  Pero ¿Qué son los modelos de negocio de TI?  Aproxímese al concepto a través de la revisión de la siguiente infografía:


    .row.align-items-center.justify-content-center.fondo-3.p-4
      .col-12.col-lg-12(data-aos="fade-left")
          img(src='@/assets/curso/images/tema3/fig_1.svg'  alt='')















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
