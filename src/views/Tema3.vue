<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Técnicas de comunicación
    
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-2(data-aos="flip-up" data-aos-duration="1000")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La comunicación efectiva de resultados analíticos representa uno de los mayores retos en proyectos de datos masivos. La capacidad de traducir análisis complejos en narrativas comprensibles determina el valor práctico de todo el trabajo analítico. Este capítulo aborda las técnicas y estrategias para comunicar resultados técnicos de manera efectiva a diferentes audiencias.
    
    Separador

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.1 Presentación de resultados
    
    p.mb-4(data-aos="fade-right") La presentación de resultados analíticos requiere un equilibrio delicado entre precisión técnica y claridad expositiva. El primer paso consiste en identificar la audiencia objetivo y adaptar el nivel de detalle técnico según sus necesidades y conocimientos previos.

    .row.align-items-center.mb-1
      .col-lg-5(data-aos="fade-right")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema3/2.png",style="max-width: 505px;")
      .col-lg-7(data-aos="fade-left")
        p.mb-4 Los resultados deben presentarse de manera estratificada, comenzando con los hallazgos más significativos y progresando hacia detalles más específicos. Esta estructura permite a cada miembro de la audiencia profundizar hasta el nivel que resulte relevante para sus necesidades.

        p.mb-4 Algunos elementos clave para una presentación efectiva incluyen:

        .fondo-color-sistema-f.py-3.px-4.mb-4
          p.mb-0 Resumen ejecutivo que destaque los hallazgos principales y su impacto

        .fondo-color-sistema-f.py-3.px-4.mb-4
          p.mb-0 Contextualización clara del problema y los objetivos del análisis

        .fondo-color-sistema-f.py-3.px-4.mb-4
          p.mb-0 Metodología explicada en términos comprensibles

        .fondo-color-sistema-f.py-3.px-4
          p.mb-0 Ejemplos concretos que ilustren los conceptos abstractos
    
    Separador

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2 Comunicación visual
    
    .row.align-items-center.mb-2
      .col-lg-7(data-aos="fade-right")
        p.mb-4 La comunicación visual transforma datos abstractos en representaciones intuitivas que facilitan la comprensión de patrones y relaciones complejas. La selección del tipo de visualización debe basarse en la naturaleza de los datos y el mensaje que se desea transmitir.
        p.mb-4 Los principios de diseño visual juegan un papel fundamental en la efectividad de la comunicación. El uso apropiado del color, la disposición espacial y la jerarquía visual guían la atención del espectador hacia los elementos más relevantes. La simplicidad y la claridad deben priorizarse sobre la complejidad visual.
        p.mb-0 En el contexto de datos masivos, las visualizaciones interactivas permiten a los usuarios explorar los datos según sus intereses específicos. Sin embargo, cada elemento interactivo debe tener un propósito claro y añadir valor a la comprensión del análisis.
      .col-lg-5.order-first.order-lg-last(data-aos="fade-left")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema3/3.png",style="max-width: 503px;")

    Separador

    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-up")
      h2 3.3 Narrativa de datos

    p.mb-4(data-aos="fade-up") La narrativa de datos transforma números y estadísticas en historias coherentes que resuenan con la audiencia. Una narrativa efectiva conecta los datos con su contexto empresarial o social, haciendo explícito su impacto y relevancia.

    .row.align-items-center.mb-4
      .col-lg-7(data-aos="fade-right")
        p.mb-4 La estructura narrativa debe seguir un arco lógico que guíe al lector desde el planteamiento del problema hasta las conclusiones y recomendaciones. Cada elemento de la historia debe construirse sobre los anteriores, creando una progresión natural que facilite la comprensión.
        p.mb-4 Los elementos fundamentales de una narrativa de datos incluyen:

        .fondo-color-sistema-f.py-3.px-4.mb-4
          p.mb-0 Un contexto claro que establezca la importancia del análisis
        .fondo-color-sistema-f.py-3.px-4.mb-4
          p.mb-0 Una progresión lógica de hallazgos que construya el argumento
        .fondo-color-sistema-f.py-3.px-4.mb-4
          p.mb-0 Puntos de inflexión que destaquen descubrimientos significativos
        .fondo-color-sistema-f.py-3.px-4
          p.mb-0 Conclusiones que conecten los hallazgos con acciones concretas

      .col-lg-5.order-first.order-lg-last(data-aos="fade-left")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema3/4.svg",style="max-width: 503px;")
    
    .row.align-items-center
      .col-lg-5(data-aos="fade-right")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema3/5.svg",style="max-width: 505px;")
      .col-lg-7(data-aos="fade-left")
        p.mb-4 La narrativa debe mantener un equilibrio entre el rigor analítico y la accesibilidad. El uso de analogías y ejemplos del mundo real puede ayudar a explicar conceptos técnicos complejos sin sacrificar la precisión.
        p.mb-4 La documentación que acompaña la narrativa debe proporcionar detalles suficientes para que otros analistas puedan reproducir y validar los resultados. Esto incluye referencias a las fuentes de datos, descripción de las transformaciones realizadas y código utilizado en el análisis.
        p.mb-4 El éxito de una narrativa de datos se mide por su capacidad para impulsar acciones basadas en los hallazgos presentados. Por ello, las recomendaciones deben ser específicas, accionables y estar respaldadas por la evidencia presentada en el análisis.
        p.mb-0 La retroalimentación de la audiencia constituye un elemento valioso para refinar y mejorar la narrativa. La capacidad de adaptar la presentación según las preguntas y comentarios recibidos demuestra dominio del tema y fortalece la credibilidad del análisis.
    


</template>

<script>
import LineaTiempoD from '../bootstrap/LineaTiempoD.vue'
export default {
  name: 'Tema3',
  components: {
    LineaTiempoD,
  },
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
