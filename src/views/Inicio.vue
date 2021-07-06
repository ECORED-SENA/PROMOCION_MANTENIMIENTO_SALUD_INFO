<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h2.mb-0 Intervenciones individuales para la promoción y mantenimiento de la salud
          
          .h3 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Intervenciones individuales para la promoción y mantenimiento de la salud
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 33110267
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Duración en semanas: 
                p.banner-principal__datos__item__texto 4 Semanas
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Requisito de ingreso: 
                .banner-principal__datos__item__texto
                  ul.lista-ul
                    li
                      i.lista-ul__vineta
                      p Profesionales de Medicina, Enfermería, Medicina Familiar, Pediatría
                   

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/INpPT67zWPw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>
            

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p La apuesta del sector plasmada en la Política de Atención Integral en Salud y que recoge los planteamientos de la ley estatutaria, se concreta en las rutas integrales de atención en salud y coloca un acento especial en la Ruta de Promoción y Mantenimiento de la Salud como herramienta esencial a ser adoptada y adaptada en todo el territorio nacional.
      br
      br
      | El presente curso “Intervenciones individuales para la promoción y mantenimiento de la salud” es el resultado de la alianza entre el Servicio Nacional de Aprendizaje -SENA- y el Ministerio de Salud y Protección Social, en sus esfuerzos por fortalecer el abordaje integral en salud.
      br
      br
      | Con el propósito de favorecer la apropiación de la Atención Integral en Salud, la Ruta de Promoción y Mantenimiento de la Salud  permite avanzar un abordaje centrado en los sujetos durante todo el curso de la vida, incorporar la familia como sujeto de atención, definir atenciones anticipatorias que permitan aportar al logro de los resultados en salud. Todo ello requiere del fortalecimiento de capacidades en el talento humano, en salud, especialmente de aquellos que brindan estas intervenciones individuales en los servicios de consulta externa.
      br
      br
      | El curso se desarrolla por actividades de aprendizaje, orientado con recursos educativos digitales y múltiples referencias que le permitirán reconocer el marco normativo y conceptual de la atención integral en salud y en el marco de la Ruta Integral para la Promoción y Mantenimiento de la Salud, ubicando elementos clave en relación a las intervenciones individuales con especial énfasis en la consulta de atención de profesional por momento de curso de vida en el marco de la valoración integral en salud, que permiten promover la salud y el desarrollo, gestionar los riesgos y definir planes de cuidado. A partir del proceso se podrán valorar los cambios que cada profesional nota en la atención que brinda tanto desde lo técnico como desde los preceptos de humanización en salud y que aportan a los resultados en salud.
      br
      br
      b Bienvenida/o

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p.mb-0 La Política de Atención Integral en Salud establecida en Resolución 429 de 2016 y modificada por Resolución 2626 de 2019, define  las rutas Integrales de Atención en Salud como los instrumentos o herramientas de uso obligatorio por parte de los diferentes integrantes del SGSSS, entre otros, Empresas Administradoras de Planes de Beneficios (EAPB), entidades territoriales, prestadores de servicios de salud, en las que se establecen las condiciones necesarias para asegurar la integralidad de la atención en salud. En este sentido, la Ruta Integral de Atención para la Promoción y Mantenimiento de la Salud y la Ruta Integral de Atención para la Población Materno – Perinatal, definen e integran las intervenciones individuales, colectivas, poblacionales y las acciones de gestión de la salud pública, requeridas para la promoción de la salud y la gestión oportuna e integral de los principales riesgos en salud de los individuos, las familias y las comunidades (cuyos lineamientos técnicos y operativos fueron adoptados mediante la Resolución 3280 de 2018). Una de las innovaciones incorporadas en las rutas, son las finalidades de valoración integral en salud y educación para la salud, que se suman a las previamente establecidas (detección temprana y protección específica). En ese sentido, se hace indispensable para la implementación adecuada de las rutas, el desarrollo de capacidades en el talento humano en salud en los procedimientos definidos en la RPMS.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Población<br>objetivo

    p.mb-0 La población objeto corresponde al talento humano en salud de nivel profesional, específicamente profesionales de Medicina, Enfermería, Medicina Familiar y Pediatría; de las direcciones territoriales y municipales de salud, IPS, EPS y otras instituciones que estén interesados, con una cobertura a nivel nacional, de acuerdo a los cupos disponibles y acordados con el SENA.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Estrategia<br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y casos reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul.mt-3
      li 
        i.fas.fa-angle-right
        | El instructor - Tutor
      li 
        i.fas.fa-angle-right
        | El entorno
      li 
        i.fas.fa-angle-right
        | Las TIC
      li 
        i.fas.fa-angle-right
        | El trabajo colaborativo

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
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
