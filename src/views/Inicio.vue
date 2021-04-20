<template lang="pug">
section
  BannerPrincipal.mb-5


  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 1. Presentación 
    p La apuesta del sector plasmada en la Política de Atención Integral en Salud y que recoge los planteamientos de la ley estatutaria , se concreta en las rutasintegrales de atención en salud y coloca un acento especial en la Ruta de Promoción y Mantenimiento de la Salud como herramienta esencial a ser adoptada yadaptada en todo el territorio nacional.
      br
      br
      | El presente curso “Intervenciones individuales para la promoción y mantenimiento de la salud” es el resultado de la alianza entre el Servicio Nacional deAprendizaje -SENA- y el Ministerio de Salud y Protección Social, en sus esfuerzos por fortalecer el abordaje integral en salud.
      br
      br
      | Con el propósito de favorecer la apropiación de la Atención Integral en Salud, la Ruta de Promoción y Mantenimiento de la Salud  permite avanzar un abordaje centrado en los sujetos durante todo el curso de la vida, incorporar la familia como sujeto de atención, definir atenciones anticipatorias quepermitan aportar al logro de los resultados en salud. Todo ello requiere del fortalecimiento de capacidades en el talento humano, en salud, especialmente deaquellos que brindan estas intervenciones individuales en los servicios de consulta externa.
      br
      br
      | El curso se desarrolla por fases, orientado con recursos educativos digitales y múltiples referencias que le permitirán reconocer el marco normativo yconceptual de la atención integral en salud y en el marco de la Ruta Integral para la Promoción y Mantenimiento de la Salud, ubicando elementos clave enrelación a las intervenciones individuales con especial énfasis en la consulta de atención de profesional por momento de curso de vida en el marco de lavaloración integral en salud, que permiten promover la salud y el desarrollo, gestionar los riesgos y definir planes de cuidado. A partir del proceso sepodrán valorar los cambios que cada profesional nota en la atención que brinda tanto desde lo técnico como desde los preceptos de humanización en saludy que aportan a los resultados en salud.
      br
      br
      b Bienvenida/o


  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 2. Justificación<br>del programa

    p La Política de Atención Integral en Salud establecida en Resolución 429 de 2016 y modificada por Resolución 2626 de 2019, define  las Rutas Integrales de Atención en Salud como los instrumentos o herramientas de uso obligatorio por parte de los diferentes integrantes del SGSSS, entre otros, Empresas Administradoras de Planes de Beneficios (EAPB) entidades territoriales, prestadores de servicios de salud, en las que se establecen las condiciones necesarias para asegurar la integralidad de la atención en salud. En este sentido, la Ruta Integral de Atención para la Promoción y Mantenimiento de la Salud y la Ruta Integral de Atención para la Población Materno – Perinatal, definen e integran las intervenciones individuales, colectivas, poblacionales y las acciones de gestión de la salud pública, requeridas para la promoción de la salud y la gestión oportuna e integral de los principales riesgos en salud de los individuos, las familias y las comunidades (cuyos lineamientos técnicos y operativos fueron adoptados mediante la Resolución 3280 de 2018). Una de las innovaciones incorporadas en las Rutas, son las finalidades de valoración integral en salud y educación para la salud, que se suman a las previamente establecidas (detección temprana y protección específica). En ese sentido, se hace indispensable para la implementación adecuada de las Rutas, el desarrollo de capacidades en el talento humano en salud en los procedimientos definidos en la RPMS.

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 3. Población<br>objetivo

    p La población objeto corresponde al talento humano en salud de nivel profesional, específicamente profesionales de Medicina, Enfermería, Medicina Familiar y Pediatría; de las direcciones territoriales y municipales de salud, IPS, EPS y otras instituciones que estén interesados, con una cobertura a nivel nacional, de acuerdo a los cupos disponibles y acordados con el SENA.

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 4. Estrategia<br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y casos reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
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
  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 Créditos

    CreditosComp

  Footer
  

</template>
<script>
import { menuPrincipal } from '../config/global'
import BannerPrincipal from '../components/plantilla/BannerPrincipal'
import CreditosComp from '../components/plantilla/CreditosComp'
import Footer from '../components/plantilla/Footer'
export default {
  name: 'Inicio',
  components: {
    BannerPrincipal,
    CreditosComp,
    Footer,
  },
  data: () => ({
    menuPrincipalData: menuPrincipal,
  }),
  computed: {
    desarrolloContenidosData() {
      const allMenuData = [
        ...this.menuPrincipalData.menu,
        ...this.menuPrincipalData.subMenu,
      ]
      return allMenuData.filter(item => item.desarrolloContenidos)
    },
  },
}
</script>

<style lang="sass" scoped>
.resultados-aprendizaje
  &__item
    margin-bottom: 20px
    &:last-child
      margin-bottom: 0

.desarrollo-contenidos
  &__item
    display: flex
    align-items: center
    justify-content: space-between
    margin-bottom: 25px
    padding: 5px
    border-radius: $base-border-radius

    &__texto
      display: flex
      align-items: center

    &__icono
      display: block
      background-color: $color-sistema-g
      font-size: 20px
      font-weight: $base-black-font-weight
      text-align: center
      padding: 10px
      line-height: 1em
      width: 40px
      margin-right: 15px

    &:last-child
      margin-bottom: 0

    &:hover
      background-color: $color-sistema-g
      font-weight: $base-black-font-weight
      color: $color-sistema-a
</style>
