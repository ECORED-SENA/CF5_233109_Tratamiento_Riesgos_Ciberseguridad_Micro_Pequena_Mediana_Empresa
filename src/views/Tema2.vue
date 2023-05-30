<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.cs
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 <i>Testing</i> y monitoreo de la seguridad digital

    .row.align-items-center.justify-content-center.mb-5
      .col-xl-4(data-aos="fade-left")
          img(src='@/assets/curso/images/tema2/img_1.png'  alt='').mb-3
      .col-xl-8(data-aos="fade-right")
        p.mb-3 La evaluación de un sistema o aplicación es el proceso de revisar, probar y evaluar los componentes, la documentación y todos los parámetros de este sistema o aplicación con el fin de garantizar que sea lo más seguro posible, dentro de la tolerancia al riesgo de una organización, mientras está operativo y se utiliza para su propósito.

        p.mb-0 De acuerdo con la Guía para la evaluación de controles de seguridad (National Institute of Standards and Technology [NIST], 2010, p. 9) un procedimiento de evaluación consiste en un conjunto de objetivos de evaluación, cada uno con un conjunto asociado de posibles métodos y objetos de evaluación, en donde cada objetivo de evaluación incluye un conjunto de declaraciones de determinación relacionadas con el control de seguridad o privacidad particular que se está evaluando. Las declaraciones de determinación están vinculadas al contenido del control de seguridad o privacidad para garantizar la trazabilidad de los resultados de la evaluación hasta los requisitos fundamentales del control. La aplicación de un procedimiento de evaluación a un control de seguridad o privacidad produce resultados de evaluación, que se reflejan en la eficacia general del control de seguridad o privacidad, determinando si el control se ha implementado correctamente, funciona según lo previsto y produce el resultado deseado en relación con los requisitos de seguridad del sistema o aplicación en cuestión (Ver figura a continuación):


    .bg-c2.my-5
      .py-5
        .row.align-items-center.justify-content-center
          .col-xl-10

            .titulo-sexto.color-acento-contenido
              h5 Figura 1
              span Evaluación de controles de seguridad

            figure.mt-5
              img(src='@/assets/curso/images/tema2/fig_1.svg', style="max-width:1240px", alt='').m-auto



    p.mb-5 Los objetos de evaluación identifican los elementos específicos que se evalúan e incluyen especificaciones, mecanismos, actividades e individuos, a continuación se puede ver en qué consisten:

    .row.mb-5
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/images/tema2/tj_1.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.fondo-2
              .row.align-items-center.justify-content-center
                img(src='@/assets/curso/images/tema2/ico_new_1.svg'  alt='', style="width:90px; display:block; margin:auto 0 ;").mb-3
              h3.text-center Especificaciones
              p.mb-0.text-center Documentación (políticas, procedimientos, planes requisitos de seguridad y privacidad, especificaciones funcionales, diseños arquitectónicos) asociados a un sistema de información.

      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/images/tema2/tj_2.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.fondo-2
              .row.align-items-center.justify-content-center
                img(src='@/assets/curso/images/tema2/ico_new_2.svg'  alt='', style="width:90px; display:block; margin:auto 0 ;").mb-3
              h3.text-center Mecanismos
              p.mb-0.text-center Salvaguardas y contramedidas específicas de #[em hardware], #[em software] o #[em firmware] empleadas en un sistema de información, es decir, los controles técnicos.

      .col-sm-6.col-xl-3.mb-4.mb-sm-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/images/tema2/tj_3.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.fondo-2
              .row.align-items-center.justify-content-center
                img(src='@/assets/curso/images/tema2/ico_new_3.svg'  alt='', style="width:90px; display:block; margin:auto 0 ;").mb-3
              h3.text-center Actividades
              p.mb-0.text-center Procesos relacionados con la protección de un sistema de información que involucran a las personas (por ejemplo, la realización de operaciones de copia de seguridad, la supervisión del tráfico de la red, la ejecución de un plan de contingencia).

      .col-sm-6.col-xl-3
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/images/tema2/tj_4.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.fondo-2
              .row.align-items-center.justify-content-center
                img(src='@/assets/curso/images/tema2/ico_new_4.svg'  alt='', style="width:90px; display:block; margin:auto 0 ;").mb-3
              h3.text-center Individuos
              p.mb-0.text-center Personas que aplican las especificaciones, los mecanismos o actividades.

    p.mb-3 El objetivo de estas distintas áreas de evaluación y su cobertura del sistema y la red en cuestión, es proporcionar pruebas de evaluación que los responsables puedan utilizar para tomar decisiones operativas desde el punto de vista de la fiabilidad, tal y como se muestra en la siguiente figura.

    .bg-c2.mt-5
      .py-5
        .row.align-items-center.justify-content-center
          .col-xl-10

            .titulo-sexto.color-acento-contenido
              h5 Figura 2
              span Sistemas de información de confiabilidad

            figure.mt-5
              img(src='@/assets/curso/images/tema2/fig_2.svg', style="max-width:819px", alt='').m-auto

    figcaption Nota. Tomado de J. Leighton (2019).


    Separador

    #t_2_1.titulo-segundo.color-acento-contenido
      .h2 2.1  Tipos

    p.mb-3 A partir de las experiencias y buenas prácticas desarrolladas por expertos en el proceso de evaluación, validación y auditoría y lo contemplado en la Guía para la evaluación de controles de seguridad (NIST, 2010), es posible determinar una secuencia de pasos a realizar durante el proceso de evaluación, como se puede observar a continuación:

    .row.justify-content-center.align-items-star.mb-5
      .col-lg-10(data-aos="fade-left")
        AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in-down")
          .row.justify-content-center.align-items-center(titulo="Revisar documentación")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_1.svg'  alt='')
            .col
              p.mb-0 Verificación de documentos existente para el sistema o la aplicación bajo prueba. Estos documentos deben proporcionar las áreas principales para el escrutinio y la evaluación.

          .row.justify-content-center.align-items-center(titulo="Revisar requisitos legales y reglamentarios")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_2.svg'  alt='')
            .col
              p.mb-0 Cada sistema debe ajustarse a políticas y reglamentos, normalmente basados en los tipos de información utilizados, procesados o mantenidos por el sistema y la misión del sistema. Identificar áreas de conformidad y concordancia sustantiva entre el sistema, sus documentos y los requisitos externos.

          .row.justify-content-center.align-items-center(titulo="Realizar el análisis GAP (15 pasos)")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_3.svg'  alt='')
            .col
              p.mb-0 Todos los documentos relevantes del sistema y de la documentación de apoyo.

          .row.justify-content-center.align-items-center(titulo="Visitar el lugar")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_4.svg'  alt='')
            .col
              p.mb-3 Primera visita de verificación del estado del sistema y de los equipos, objetivo primordial para identificar áreas potenciales de preocupación o sospecha.
              p.mb-0 Gestión de las expectativas del personal y la Dirección, sobre el proceso.

          .row.justify-content-center.align-items-center(titulo="Construir SAP y ROE")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_5.svg'  alt='')
            .col
              p.mb-0 Desarrollar el Plan de Evaluación de Seguridad (SAP) que define los pasos, herramientas y técnicas de revisión que se aplicarán durante la evaluación.  También se definen las Reglas de Compromiso (ROE) para toda la evaluación, incluyendo la realización de cualquier prueba externa, entrevistas e inspecciones según lo requerido por la organización.

          .row.justify-content-center.align-items-center(titulo="Aprobar SAP y ROE")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_6.svg'  alt='')
            .col
              p.mb-0 Presentar el SAP y las ROE para su aprobación y aceptación al responsable de la contratación.  La visita de evaluación propiamente dicha, no debe comenzar hasta haber recibido los documentos aprobados y firmados por medios oficiales.

          .row.justify-content-center.align-items-center(titulo="Realizar la evaluación")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_7.svg'  alt='')
            .col
              p.mb-0 Una vez aprobados el SAP y las ROE, se programa la visita <em>in situ</em> para llevar a cabo las actividades de evaluación propiamente dichas. Importante preparación para la visita familiarizándose con las herramientas del oficio y documentación del sistema para realizar correctamente las entrevistas y los exámenes.

          .row.justify-content-center.align-items-center(titulo="Visita <em>in situ</em>")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_8.svg'  alt='')
            .col
              p.mb-0 Suele comenzar con una reunión informativa con la dirección, en la que se discuten las expectativas de la visita, se reconfirma la programación de las entrevistas y se presenta el equipo al personal del lugar.

          .row.justify-content-center.align-items-center(titulo="Entrevistar al personal clave")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_9.svg'  alt='')
            .col
              p.mb-0 Entrevistas con el personal operativo clave del sistema, el director de las instalaciones del lugar, el personal de seguridad tanto del lugar como del sistema, el propietario del sistema, los miembros del personal de administración del sistema del lugar y del sistema, así como cualquier desarrollador asociado con el sistema.

          .row.justify-content-center.align-items-center(titulo="Examinar el sistema")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_10.svg'  alt='')
            .col
              p.mb-0 Obtener una demostración por parte del personal para observar el procesamiento y los controles de seguridad en acción, así como las actividades de entrada y salida del sistema (control de acceso, identificación y autenticación, integridad, protección del sistema, comunicaciones).

          .row.justify-content-center.align-items-center(titulo="Llevar a cabo una inspección de recorrido de seguridad")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_11.svg'  alt='')
            .col
              p.mb-0 Verificación de controles físicos y ambientales, de mantenimiento, de protección de medios y de planificación de contingencias del sistema (controles de extinción y detección de incendios, sistema de calefacción, ventilación y aire acondicionado, servicios públicos y acceso físico, capacidad de alimentación de reserva de la ubicación empleada dentro del sistema).

          .row.justify-content-center.align-items-center(titulo="Probar el sistema con las herramientas definidas en SAP")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_12.svg'  alt='')
            .col
              p.mb-0 Para obtener pruebas de cumplimiento y configuraciones de control de seguridad:
              p.mb-0 -Herramientas de escaneo: escáneres de bases de datos, de vulnerabilidad, de sitios web, mapeadores de red.
              p.mb-0 -Herramientas automatizadas: comprobadores de la integridad de los archivos, detección de redes inalámbricas, pruebas de penetración para comprobar conjuntos de controles de seguridad.

          .row.justify-content-center.align-items-center(titulo="Análisis inicial de los resultados")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_13.svg'  alt='')
            .col
              p.mb-0 Una vez finalizada la ejecución de la(s) herramienta(s) a través de sus operaciones, revisar los resultados para identificar deficiencias o debilidades de alto o medio impacto. Además, se revisan los resultados de la prueba para asegurar que se ha completado con éxito.

          .row.justify-content-center.align-items-center(titulo="Informe de corrección para la toma de medidas")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_14.svg'  alt='')
            .col
              p.mb-0 Cada herramienta utilizada proporciona un método para la identificación de los problemas descubiertos.  Esos datos se proporcionan al personal de administración del sistema, a través de informe que permita corregir cualquier deficiencia o debilidad de impacto significativo tan pronto como sea posible.

          .row.justify-content-center.align-items-center(titulo="Recibir pruebas del artefacto de esfuerzo de reparación")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_15.svg'  alt='')
            .col
              p.mb-0 El personal <em>in situ</em> del sistema permite ejecutar nuevamente las herramientas automatizadas para verificar la reparación o la prueba de la reparación mediante el uso de "capturas de pantalla" o informes de salida de los dispositivos.  Estos documentos y artefactos se adjuntan o se incluyen en el SAR.

          .row.justify-content-center.align-items-center(titulo="Construir el SAR")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_16.svg'  alt='')
            .col
              p.mb-0 Comienza durante la fase de pruebas revisando los resultados de los exámenes y las entrevistas.  Finalizada dicha fase y entregado el Informe de reparación, se incluyen los resultados de los escaneos y otras pruebas realizadas.  Finalmente, se incluyen todas las áreas, junto con una tabla completa de resultados por control.

          .row.justify-content-center.align-items-center(titulo="Revisar el SAR con el cliente")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_17.svg'  alt='')
            .col
              p.mb-0 Se revisan los resultados preliminares para señalar cualquier área o elemento que pueda arreglarse, repararse o remediarse antes de la entrega final. A menudo, el cliente aborda algunas o todas estas áreas y proporciona documentación de apoyo adicional o prueba de la corrección, que se incluye en el SAR final.

          .row.justify-content-center.align-items-center(titulo="Desarrollar el SAR final")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_18.svg'  alt='')
            .col
              p.mb-0 Una vez terminadas todas las revisiones y discusiones, se completa el SAR en su versión final y se prepara el #[em briefing] para el AO que acompañará al informe.

          .row.justify-content-center.align-items-center(titulo="Elaborar la carta de certificación")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_19.svg'  alt='')
            .col
              p.mb-0 Completado el SAR y las revisiones del SSP como resultado de la evaluación, se genera una Carta de Certificación para el AO indicando los resultados de la evaluación y la opinión del evaluador sobre los riesgos del sistema.

          .row.justify-content-center.align-items-center(titulo="Entregar el informe de evaluación y la carta de certificación al propietario del sistema y al cliente")
            .col-auto
              img(src='@/assets/curso/images/tema2/ico_20.svg'  alt='')
            .col
              p.mb-0 Último paso del proceso que implica entregar el SAR final, la versión final del SSP y la Carta de recomendación al AO y al propietario del sistema para que tomen medidas.

    Separador

    #t_2_2.titulo-segundo.color-acento-contenido
      .h2 2.2  Características

    .row.justify-content-center.align-items-star.mb-3
      .col-lg-12
        .bloque-texto-g.color-custom-3.p-3.p-sm-4.p-md-5.mb-5.d-none.d-lg-block
          .bloque-texto-g__img(data-aos="fade-right")(
            :style="{'background-image': `url(${require('@/assets/curso/images/tema2/img_2.png')})`}"
          )
          .bloque-texto-g__texto.p-5.m-right(data-aos="fade-left")
            p.mb-3 Para llevar a cabo la evaluación de un sistema o aplicación, hay que centrarse inicialmente en las áreas de mayor impacto, mayor valor y mayor volatilidad. Una vez determinado esto, el enfoque se desplaza al resto del sistema o aplicación para cubrir todas las posibles áreas de impacto, ya que, en el ámbito de la seguridad, hoy en día es posible cualquier método de ataque o entrada en el sistema.
            br
            p.mb-0 Según la SP 800-115, algunas evaluaciones se centran en verificar que un control de seguridad concreto (o un conjunto de controles) cumple los requisitos, mientras que otras evaluaciones pretenden identificar, validar y valorar los puntos débiles de seguridad explotables de un sistema. Las evaluaciones también se realizan para aumentar la capacidad de una organización para mantener una defensa proactiva de la red informática. En todo caso, las evaluaciones no pretenden sustituir la implementación de controles de seguridad y el mantenimiento de la seguridad del sistema.

    .row.justify-content-center.align-items-star.mb-3
      .col-lg-10
        .cajon-b.color-primario.p-3.mb-5
          p.mb-3 El enfoque especializado de un evaluador es necesario cuando el sistema bajo prueba o la aplicación en cuestión se encuentra en un entorno de alta volatilidad, acaba de remediar problemas de seguridad que se han reparado, o requiere una revisión de verificación y validación independiente para futuras operaciones en una red federal.

          p.mb-0 El NIST en la Guía para la evaluación de controles de seguridad (2010), hace las siguientes recomendaciones a las organizaciones interesadas en llevar a cabo evaluaciones técnicas de seguridad y garantizar que las pruebas y exámenes técnicos de seguridad proporcionen el máximo valor:
      .col-8.col-lg-2
        img(src='@/assets/curso/images/tema2/img_3.svg'  alt='')

    .row.justify-content-center.align-items-star.mb-5
      .col-8.col-lg-4(data-aos="fade-left")
          img(src='@/assets/curso/images/tema2/img_4.svg'  alt='')
      .col-lg-8(data-aos="fade-right")
        LineaTiempoD.color-secundario.especial
          .row(titulo='Establecer una política de evaluación de la seguridad de la información' numero='1')
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 La política debe identificar los requisitos de la organización para la realización de evaluaciones responsabilizando a las personas adecuadas para garantizar que las evaluaciones se realizan de acuerdo con estos requisitos.
          .row(titulo='Aplicar una metodología de evaluación' numero='2')
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 Metodología repetible y documentada que proporcione:
                ul.lista-ul--color.mt-3
                  li
                    i.vineta-1(data-aos="fade-up")
                    p.mb-0 Coherencia y estructura a las evaluaciones.
                  li
                    i.vineta-1(data-aos="fade-up")
                    p.mb-0 Acelere la transición del nuevo personal de evaluación.
                  li
                    i.vineta-1(data-aos="fade-up")
                    p.mb-0 Aborde las limitaciones de recursos asociadas a las evaluaciones.
                  li
                    i.vineta-1(data-aos="fade-up")
                    p.mb-0 Permita a las organizaciones maximizar el valor de las evaluaciones al tiempo que minimiza los posibles riesgos introducidos por ciertas técnicas de evaluación.
          .row(titulo='Analizar los hallazgos y desarrollar técnicas de mitigación de riesgos para abordar los puntos débiles' numero='3')
            .col-md-12.col-lg-12.mb-4.mb-md-0
              p.mb-0 Las organizaciones deben realizar un análisis de las causas raíz al finalizar una evaluación para poder traducir los resultados en técnicas de mitigación procesables. Estos resultados pueden indicar que las organizaciones deben abordar no sólo las debilidades técnicas, sino también debilidades en procesos y procedimientos.

    p.mb-3 Dentro del marco del proceso RMF, el SP 800-53A proporciona la guía especializada y el flujo del proceso para llevar a cabo las pruebas reales y los eventos de evaluación en cada control de seguridad implementado en el sistema o aplicación bajo evaluación. El paso 4 del RMF - evaluación - es el paso dirigido dentro del RMF (SP 800-37, rev. 1) que proporciona la guía general para llevarlo a cabo (ver figura).


    .bg-c2.my-5
      .py-5
        .row.align-items-center.justify-content-center
          .col-xl-10

            .titulo-sexto.color-acento-contenido
              h5 Figura 3
              span RMF Paso 4 - Evaluar los controles de seguridad

            figure.mt-5
              img(src='@/assets/curso/images/tema2/fig_3.svg', style="max-width:988px", alt='').m-auto


    .btn-h3.mb-4
      span.h3 Métodos de evaluación

    .row.align-items-center.justify-content-center.mb-5
      .col-lg-8(data-aos="fade-left")
        p.mb-3 Los métodos y procedimientos de evaluación se utilizan para determinar si los controles de seguridad se aplican correctamente, funcionan como se pretende y producen el resultado deseado con respecto al cumplimiento de los requisitos de seguridad de la organización. Las organizaciones utilizan los procedimientos de evaluación recomendados en el SP 800-53A como punto de partida para desarrollar procedimientos de evaluación más específicos, que pueden, en ciertos casos, ser necesarios debido a las dependencias de la plataforma u otras consideraciones relacionadas con la implementación. El empleo de procedimientos de evaluación estandarizados promueve evaluaciones de seguridad más consistentes, comparables y repetibles de los sistemas de información.
        p.mb-3 A continuación se pueden revisar los tipos de métodos de evaluación que se pueden utilizar:
      .col-12.col-lg-4(data-aos="fade-right")
          img(src='@/assets/curso/images/tema2/img_5.jpg'  alt='')


    .tarjeta.bg_grad-01.p-4.mb-5(data-aos="zoom-in-up")
      SlyderA(tipo="b")
        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Prueba
            p.mb-3 Es el proceso de ejercitar uno o más objetos de evaluación bajo condiciones específicas para comparar los comportamientos reales y los esperados.

          .col-12.col-lg-5(data-aos="fade-right")
              img.mt-5(src='@/assets/curso/images/tema2/img_6.png'  alt='')

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Examen
            p.mb-0 Comprobación, inspección, revisión, observación, estudio o análisis de uno o más objetos de evaluación para facilitar la comprensión, lograr una aclaración u obtener pruebas. Implica principalmente la revisión de documentos para identificar el diseño, instalación, configuración, funcionamiento y el mantenimiento previstos de los sistemas y la red, y su revisión y referencias cruzadas garantizan la conformidad y la coherencia.

          .col-12.col-lg-5(data-aos="fade-right")
              img.mt-5(src='@/assets/curso/images/tema2/img_7.png'  alt='')

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Entrevista
            p.mb-0 Discusiones con individuos o grupos dentro de una organización para facilitar la comprensión, lograr la aclaración o identificar la ubicación de las pruebas.
          .col-12.col-lg-5(data-aos="fade-right")
              img.mt-5(src='@/assets/curso/images/tema2/img_8.png'  alt='')

        .row.align-items-center.justify-content-center.mb-5
          .col-lg-5
            h3.mb-3 Revisión de la documentación
            p.mb-0 Determina si los aspectos técnicos de las políticas y procedimientos están actualizados y son completos.  La documentación incluye arquitecturas y requisitos de seguridad, planes de seguridad del sistema, acuerdos de autorización, memorandos de entendimiento y los acuerdos para las interconexiones del sistema, y planes de respuesta a incidentes.
          .col-12.col-lg-5(data-aos="fade-right")
              img.mt-5(src='@/assets/curso/images/tema2/img_9.png'  alt='')

    .btn-h3.mb-4
      span.h3 #[i Testing]


    .row.align-items-center.justify-content-center.mb-5
      .col-lg-8(data-aos="fade-left")
        p.mb-3 Las pruebas implican un trabajo práctico con sistemas y redes para identificar las vulnerabilidades de seguridad, y pueden ejecutarse en toda una empresa o en sistemas seleccionados. El uso de técnicas de escaneo y penetración puede proporcionar información valiosa sobre posibles vulnerabilidades y predecir la probabilidad de que un adversario o intruso sea capaz de explotarlas. Las pruebas también permiten a las organizaciones medir los niveles de cumplimiento en áreas como la gestión de parches, la política de contraseñas y la gestión de la configuración.

        p.mb-0 Aunque las pruebas pueden proporcionar una imagen más precisa de la postura de seguridad de una organización que la que se obtiene a través de los exámenes, son más intrusivas y pueden afectar a los sistemas o redes del entorno objetivo. El nivel de impacto potencial depende de los tipos específicos de técnicas de prueba utilizados, que pueden interactuar con los sistemas y redes de destino de varias maneras, como el envío de paquetes de red normales para determinar los puertos abiertos y cerrados, o el envío de paquetes especialmente diseñados para probar las vulnerabilidades. Cada vez que una prueba o probador interactúa directamente con un sistema o red, existe la posibilidad de que se produzcan paradas inesperadas del sistema y otras condiciones de denegación de servicio. Las organizaciones deben determinar sus niveles aceptables de intrusión cuando decidan qué técnicas utilizar. Excluir las pruebas conocidas por crear condiciones de denegación de servicio y otras interrupciones puede ayudar a reducir estos impactos negativos.
      .col-10.col-lg-4(data-aos="fade-right")
          img(src='@/assets/curso/images/tema2/img_10.svg'  alt='')

    Separador

    #t_2_3.titulo-segundo.color-acento-contenido
      .h2 2.3 #[em Software]

    p.mb-5 Se debe revisar cada detalle en la siguiente infografía, sobre los métodos de evaluación y lineamientos establecidos en relación al #[em software]:

    .row.justify-content-center.align-items-center
      .col-lg-10(data-aos="zoom-in-down")
        .tarjeta.color-secundario.px-4.py-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/images/tema2/ico_pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1.text-white Métodos de Evaluación
                  p.text-white.mb-0.text-small Para conocer más a detalle los métodos de evaluación, lo invitamos a consultar el siguiente PDF.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/anexo_metodos.pdf')" target="_blank")
                    span.color-btn-texto Ver pdf
                    i.far.fa-file-pdf


</template>

<script>
export default {
  name: 'Tema2',
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
