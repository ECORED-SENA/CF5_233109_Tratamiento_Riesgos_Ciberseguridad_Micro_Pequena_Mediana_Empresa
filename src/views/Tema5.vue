<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.cs
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Técnicas de recopilación de información <i>(Information gathering)</i>


    .row.justify-content-center.align-items-center
      .col-auto.onTop
        .p-5.p-lg-0
          img.mb-3(src="@/assets/curso/images/tema5/img_1.svg" alt='', style="width:430px;").m-auto
      .col-lg
        .custom_box_left
          p.mb-3 Cuando se lleva a cabo la vigilancia y el reconocimiento digital, una de las prioridades es reunir información sobre un objetivo o un grupo de objetivos. Con los progresos del ámbito digital, se puede estar en un terminal de ordenador o en un dispositivo móvil en cualquier parte del mundo, conectarse a la Internet pública y reunir gran cantidad de información sobre variedad de objetivos en cuestión de minutos, todo ello sin ser detectado.

          p.mb-0 Esto tiene gran importancia en primer lugar, porque para poder atacar, hay que encontrar vectores en los que se pueda vulnerar el objetivo.  Hoy día, con la tecnología digital es evidente el creciente vector de ataque.  Una conversación telefónica, por ejemplo, puede ser almacenada digitalmente dentro de un dispositivo de cambio de rama privada, de forma local en el teléfono o capturada en la transmisión y colocar aplicaciones en el dispositivo receptor para escuchar la conversación. Hay más puntos en la transmisión para capturar datos y más lugares en los que se almacenan.

    p.my-4 Asumida la posibilidad de recopilar información de forma rápida y fácil, es necesario considerar todos los puntos en los que se puede recopilar. Así entendido el vector de ataque, considerar si la información es realmente privada y para adelantar entonces medidas de protección y mitigar los ataques.

    Separador

    #t_5_1.titulo-segundo.color-acento-contenido
      .h2 5.1  Tipos

    .row.align-items-center.justify-content-center.mb-5
      .col-lg-7(data-aos="fade-left")
        p.mb-3 A medida que se centralizan más y más datos, y las herramientas evolucionan para hacer un mejor trabajo de extracción de información clave, la capacidad de utilizar esto para el espionaje crece exponencialmente. Los big data y la informática/analítica son las principales áreas de crecimiento tecnológico en la actualidad, respondiendo a la necesidad de las organizaciones de aprovechar los datos almacenados para obtener resultados específicos.

        p.mb-3 Existen muchas herramientas de vigilancia, las que realizan tareas específicas de recopilación de información y otras en las que se puede recopilar y correlacionar información, algunas de ellas se destacan en la siguiente imagen:
      .col-12.col-lg-5(data-aos="fade-right").d-none.d-lg-block
          img(src='@/assets/curso/images/tema5/img_2.png'  alt='')

    .row.mb-5(data-aos="fade-right")
      .col-12.bg-color9
        .p-1.p-lg-5
          ImagenInfografica.color-acento-botones
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/images/tema5/info2.svg')
            .tarjeta.color-custom-6.p-3(x="26%" y="10%" numero="+")
              .h5.mb-2 La amenaza de Internet
              p.mb-0 Una o varias herramientas que permitan tomar datos desde sitio de internet como páginas web, formularios o servicios de aplicaciones.
            .tarjeta.color-custom-6.p-3(x="26%" y="26%" numero="+")
              .h5.mb-2 Motores de búsqueda
              p.mb-0 Herramienta para hacer consultas de información usando frases o palabras clave. Identificar aquellos motores que permitan consultas sin traer enlaces o programas maliciosos.
            .tarjeta.color-custom-6.p-3(x="74%" y="19%" numero="+")
              .h5.mb-2 Escaneado, olfateo y mapeo
              p.mb-0 Uso de herramientas y aplicaciones de #[em software], para la intersección de paquetes que pasan por las redes de datos. La idea es capturar la información con fines de prevención o corrección.
            .tarjeta.color-custom-6.p-3(x="26%" y="42%" numero="+")
              .h5.mb-2 Phishing
              p.mb-0 Práctica delictiva utilizada para tomar información bancaria y hacer fraudes a gran escala.
            .tarjeta.color-custom-6.p-3(x="26%" y="58%" numero="+")
              .h5.mb-2 Rastreo
              p.mb-0 Uso de aplicaciones de #[em software] que permite hacer el seguimiento de la huella digital de usuarios con propósitos poco éticos.
            .tarjeta.color-custom-6.p-3(x="26%" y="74%" numero="+")
              .h5.mb-2 Redes sociales
              p.mb-0 En estas aplicaciones web, los datos son el mayor tesoro, ya que se ofrecen de forma libre, pero pueden quedar expuestos para diferentes acciones.
            .tarjeta.color-custom-6.p-3(x="26%" y="90%" numero="+")
              .h5.mb-2 Robo de identidad
              p.mb-0 Actividad en donde se toma la información de un usuario y se usa de forma inapropiada en Internet y servicios de banca.
            .tarjeta.color-custom-6.p-3(x="74%" y="35%" numero="+")
              .h5.mb-2 Conectado e inalámbrico
              p.mb-0 Se revisan todos los conceptos, facilidades y vulnerabilidades presentes en redes de datos, en función del medio de transmisión.
            .tarjeta.color-custom-6.p-3(x="74%" y="50%" numero="+")
              .h5.mb-2 Amenaza de dispositivos móviles
              p.mb-0 Los dispositivos móviles se han convertido en un punto de entrada a las redes de datos que pueden explotar las vulnerabilidades de la red o el sistema de información.
            .tarjeta.color-custom-6.p-3(x="74%" y="66%" numero="+")
              .h5.mb-2 Seguimiento y acoso
              p.mb-0 Técnicas para obtener información a través de acciones físicas de seguimiento e intimidación.
            .tarjeta.color-custom-6.p-3(x="74%" y="82%" numero="+")
              .h5.mb-2 Ingeniería social
              p.mb-0 Técnicas para obtener información sin que la persona se dé cuenta de que se está vulnerando sus opciones de seguridad.

    Separador

    #t_5_2.titulo-segundo.color-acento-contenido
      .h2 5.2  Características

    p.mb-3 A continuación se ven las características de las principales técnicas de recopilación de información, determinando su alcance y relevancia:

    .row.justify-content-center.align-items-star.mb-5
      .col-lg-10(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in-down")
          .row.justify-content-center.align-items-center(titulo="La amenaza de Internet")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_1.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 La red pública de Internet es una “mina de oro” para quienes realizar labores de inteligencia.  Utilizada de forma no maliciosa resulta extremadamente útil, pero puede servir para reunir información y dirigir ataques.  Otro punto es que una vez se sube algo en un servidor (entrada de blog, archivo de datos) podría permanecer allí durante mucho tiempo, posiblemente para siempre.

          .row.justify-content-center.align-items-center(titulo="Motores de búsqueda")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_2.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Proporcionan gran cantidad de información a quienes saben cómo utilizarla. Las búsquedas de palabras clave y el refinamiento de los temas, así como el uso de herramientas y sitios web específicos, pueden dar a un atacante todo lo que necesita para comenzar la vigilancia de un objetivo.

          .row.justify-content-center.align-items-center(titulo="Phishing")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_3.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 En el phishing, un atacante puede hacerse pasar por una fuente legítima en Internet para engañar, haciendo creer al usuario que está en la entidad que intenta visitar. Al buscar en Internet, puede encontrar (o ir directamente a) un sitio web en el que desea realizar una operación. Por ejemplo, una cuenta bancaria en línea para realizar una transacción.

          .row.justify-content-center.align-items-center(titulo="Rastreo")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_4.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Otra forma de recopilar de información es a través de sitios web que rastrean quién es el usuario y de dónde viene. Esto puede utilizarse con fines de marketing, pero en manos de quienes desean hacer daño, puede utilizarse para rastrear intereses, ubicación, dispositivos digitales (como el PC) y datos de identidad.


          .row.justify-content-center.align-items-center(titulo="Redes sociales")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_5.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Están apareciendo en masa ofreciendo una manera de hacer negocios, compartir datos, conocer personas, encontrar nuevas oportunidades.  Pero, conlleva una gran responsabilidad en cuanto a la información que se comparte.  No debería sorprender que cuando una residencia es robada durante, por ejemplo, un período de vacaciones, la primera pregunta que se haga sea: ¿sabía alguien que estaba fuera?

          .row.justify-content-center.align-items-center(titulo="Escaneado, olfateo y mapeo")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_6.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Las redes cableadas se perciben más seguras que las inalámbricas, haciendo más difícil recopilar información por la dificultad de penetrar un cable para extraer información, pudiendo estropearlo y acabar con las señales que transportan la información. También producen por lo general una mayor velocidad de transmisión. Su principal debilidad: el tendido del cableado, costoso y más difícil de mantener.

          .row.justify-content-center.align-items-center(titulo="Conectado e inalámbrico")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_7.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 Examinan los niveles inferiores de las comunicaciones digitales, principalmente en la red a través de herramientas para capturar datos y realizar análisis a nivel de paquetes o escrutinio de puertos para reunir y verificar información sobre un objetivo.

          .row.justify-content-center.align-items-center(titulo="Amenaza de dispositivos móviles")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_8.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 La mayor tendencia actual es el uso del dispositivo móvil, capaz de conectarse a las redes, incluida Internet, de forma inalámbrica.  Pero fácilmente manipulable por un usuario malintencionado debido a por ejemplo, la posibilidad de instalar aplicaciones de #[em software] (o apps, para abreviar) proveniente de muchas fuentes, que podría incluir #[em software] malicioso.

          .row.justify-content-center.align-items-center(titulo="Amenaza de datos (metadatos)")
            .col-auto
              img(src='@/assets/curso/images/tema5/ico_9.svg'  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              p.mb-0 No hay mayor amenaza que ser rastreado en línea. Por ejemplo, al hacer fotos a través de teléfono inteligente, la información se almacena en metadatos, que permiten archivar imágenes y saber cuándo y dónde fueron tomadas.  Pero también, puede ser una fuente para que acosadores localicen ubicaciones exactas.



    Separador

    #t_5_3.titulo-segundo.color-acento-contenido
      .h2 5.3  Aplicación

    p.mb-3 Las técnicas de recolección de información pueden ser aplicadas a través de varias formas o tácticas que se detallan a continuación:

    .tarjeta.bg_grad-01.p-4.mb-5(data-aos="zoom-in-up")
      SlyderA(tipo="b")
        .row.align-items-center.justify-content-center
          .col-md-12.col-xl-5.mb-4.mb-xl-0
            .px-4.pt-4.px-0
              h3.mb-3 Seguimiento y acoso
              p.mb-3 Una de las formas más antiguas de investigación, recopilación de información o técnica de acoso es seguir físicamente a alguien sin su conocimiento. Acechar a un objetivo se considera seguirlo, a veces para obtener información y a veces para hacerle daño.

              p.mb-0 No hay forma de explicar cómo se puede hacer esto sin decir que la clave es pasar desapercibido (es decir, ser sigiloso), permanecer fuera de la vista, pero no tanto como para perder.


          .col-md-12.col-xl-5
            img(src='@/assets/curso/images/tema5/img_3.png'  alt='')

        .row.align-items-center.justify-content-center
          .col-md-12.col-xl-5.mb-4.mb-xl-0
            .px-4.pt-4.px-0
              h3.mb-3 Ingeniería social
              p.mb-3 Implica engañar a alguien a través de una conversación para obtener información particular.  Por ejemplo, llamar desde un número de teléfono falsificado que parece confiable, contar cosas de interés, y a través de preguntas específicas lograr acceso a un sitio web o una cuenta bancaria.
              p.mb-0 Existen herramientas de #[em software] como Backtrack que pueden cargar programas de ingeniería social para la realización de dichos ataques.


          .col-md-12.col-xl-5
            img(src='@/assets/curso/images/tema5/img_4.png'  alt='')

        .row.align-items-center.justify-content-center
          .col-md-12.col-xl-5.mb-4.mb-xl-0
            .px-4.pt-4.px-0
              h3.mb-3 Búsqueda en el contenedor de basura
              p.mb-3 Enseña al sistema a considerar varias condiciones antes de activar la alarma.
              p.mb-3 Consiste en rebuscar en la basura para recoger datos que se hayan desechado y que puedan contener información personal para utilizar maliciosamente.

          .col-md-12.col-xl-5(data-aos="fade-right")
            img(src='@/assets/curso/images/tema5/img_5.png'  alt='')


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
