<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0.text-white Atención y servicio al ciudadano
          
          .h2.text-white Información del programa
          .banner-principal__datos
            ul.text-white
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Atención y servicio al ciudadano
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 9120002
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto N/A
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo 
                .banner-principal__datos__item__texto
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe width="560" height="315" src="https://www.youtube.com/embed/1VhhBnNLpi0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                            

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p La atención y servicio al ciudadano es el punto de encuentro e interacción que los habitantes del país, como parte de la comunidad en general, tienen con las instituciones públicas, el gobierno y estado, permitiéndoles realizar consultas o radicar requerimientos específicos según la entidad; siendo las entidades las garantes del cumplimiento y generación de la información sobre la gestión, resultados y respuestas específicas a los ciudadanos que lo requieran.

    p Durante el curso se detalla la atención al ciudadano como mecanismo que permite y facilita que las entidades reciban las expresiones, manifestaciones y demandas de información, de beneficios, y demás servicios que requieran los colombianos. El servicio en sí es el otorgamiento y cumplimiento de los requerimientos que el ciudadano solicita y requiere, por parte de la entidad pública o de gobierno, y debe ser oportuno, de calidad y que supla las necesidades del ciudadano.

    p En una sociedad cada vez más grande y plural, el servicio público debe ser mucho más amplio y extenso, de tal manera que las capacidades institucionales y de quienes son sus funcionarios logren dar respuesta y alleguen con sus servicios a la población que lo requiera en modo y lugar; de ahí que es vital, que las instituciones públicas se ajusten permanentemente en pro del mejoramiento continuo sus protocolos de actuación en atención generando eficiencia y nuevos modelos que favorezcan la pluralidad de ciudadanos en el territorio nacional. Razón por la cual la atención y el servicio al ciudadano está tomando un apoyo en las tecnologías de la información y la comunicación TIC, lo que facilita un mayor alcance y oportunidad en las respuestas.

    p.mb-0 Así mismo el programa se sustenta en la normativa actual respecto a la atención al ciudadano en las entidades públicas (NTC GP 1000), en concordancia con el Programa Nacional del Servicio al Ciudadano liderado por el Departamento Nacional de Planeación, bajo el marco del Modelo de Gestión Pública Eficiente de Servicio al Ciudadano establecido en el CONPES 3785 de 2013 y que, en uno de sus lineamientos de trabajo llamado ventanilla hacia adentro, contempla la importancia de la formación del talento humano (funcionarios públicos) en todo lo relacionado con la atención y servicio al ciudadano bajo estándares de calidad y eficiencia.  


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p En 2019, la Encuesta realizada por el DANE de Cultura Política, permitió identificar un crecimiento  entre el 2017 y el 2019 de los ciudadanos que acudieron a los servicios prestados por las entidades públicas pasando del 19.0% al 25.9% de la población colombiana, de esa población el 35% asoció su respuesta con la necesidad de resolver un asunto y el 21.2% con demoras en obtención de la información; lo que expresa la necesidad de las entidades públicas  de contar con mayores capacidades de atención al ciudadano, así como de contar con talento humano con las competencias, el suficiente y eficiente cumplimiento de sus funciones en favor de la calidad y oportunidad que generen satisfacción al ciudadano.

    p.mb-0 El curso de Atención y Servicio al Ciudadano impartido por el SENA, en la modalidad de Formación Complementaria, está dirigido a todos los funcionarios públicos de las entidades públicas y del Estado, y está orientado especialmente al procedimiento de atención al ciudadano, enmarcado en una cultura de mejoramiento continuo del servicio; dando respuesta además a la normativa actual respecto a la atención al ciudadano en las entidades públicas en concordancia con el Programa Nacional del Servicio al Ciudadano liderado por el Departamento Nacional de Planeación-DNP, bajo el marco del Modelo de Gestión Pública Eficiente de Servicio al Ciudadano establecido en el CONPES 3785 de 2013 y que, en uno de sus lineamientos de trabajo llamado ventanilla hacia adentro, contempla la importancia de la formación del talento humano (funcionarios públicos), en todo lo relacionado con la atención y servicio al ciudadano bajo estándares de calidad y eficiencia. En un ambiente autónomo y flexible que permita al ritmo del interesado apropiar y sensibilizar la importancia del desarrollo de conocimientos y competencias en pro de un mejor servicio y atención al ciudadano.
 

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a<br> desarrollar

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | 210601020. Atender clientes de acuerdo con procedimiento de servicio y normativa.     
      
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de <br> ingreso

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | Personas naturales mayores de 18 años de edad.    
      li 
        i.lista-ul__vineta
        | Título de bachiller.  
      li 
        i.lista-ul__vineta
        | Dos meses de experiencia en atención al cliente.    
      li 
        i.lista-ul__vineta
        | Conocimientos en ofimática (con conexión a internet).    


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Estrategia metodológica

    p Centrada en la autonomía del estudiante, con asistencia del tutor para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

    p Igualmente, se estimula de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:   

    p.p1 - El instructor – Tutor
    p.p1 - El entorno
    p.p1 - Las TIC
    p.p1 - El trabajo colaborativo    


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 7. Creditos
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
