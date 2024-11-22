<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Informes técnicos avanzados
    
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-2(data-aos="flip-up" data-aos-duration="1000")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los informes técnicos avanzados constituyen una herramienta fundamental para comunicar resultados, metodologías y hallazgos en proyectos de analítica de datos. La capacidad de transmitir información técnica compleja de manera clara y estructurada determina en gran medida el impacto y la utilidad de los análisis realizados. Este capítulo explora las metodologías y mejores prácticas para la creación y gestión de informes técnicos efectivos.
    
    Separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Estructura y organización

    .row.align-items-center.mb-4
      .col-lg-7(data-aos="fade-right")
        p.mb-4 La estructuración efectiva de un informe técnico requiere un balance entre rigor metodológico y claridad expositiva. La organización jerárquica de la información permite a los lectores navegar el contenido según sus necesidades específicas, desde resúmenes ejecutivos hasta detalles técnicos profundos.
        p.mb-0 Para comprender mejor los elementos constitutivos de un informe técnico avanzado y su propósito, consideremos la siguiente estructura estándar y sus componentes:

      .col-lg-5.order-first.order-lg-last(data-aos="fade-left")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema2/2.png",style="max-width: 505px;")
    
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      p.mb-0 #[b Tabla 2.] Elementos que integran un informe técnico avanzado
    
    .tabla-a.color-primario.mb-4(data-aos="fade-up")
      table
        caption.fw-normal #[strong Fuente.] OIT, 2024.
        thead
          tr.text-white.text-center(style="background-color:#03A9F4;")
            th Sección
            th Contenido principal
            th Audiencia objetivo
            th Nivel de detalle técnico
            th Extensión recomendada
        tbody.text-center
          tr.bg-white
            td Resumen ejecutivo
            td Hallazgos clave y recomendaciones
            td Gerencia y tomadores de decisiones
            td Bajo - enfoque en impacto
            td 1-2 páginas
          tr.bg-white
            td Introducción
            td Contexto, objetivos y alcance
            td Todos los #[em stakeholders]
            td Medio - marco general
            td 2-3 páginas
          tr.bg-white
            td Metodología
            td Técnicas y herramientas utilizadas
            td Equipo técnico y analistas
            td Alto - detalles específicos
            td 3-5 páginas
          tr.bg-white
            td Análisis de datos
            td Procesamiento y resultados
            td Analistas y expertos del dominio
            td Alto - análisis detallado
            td 5-10 páginas
          tr.bg-white
            td Visualizaciones
            td Gráficos y #[em dashboards]
            td Todos los #[em stakeholders]
            td Medio - interpretación clara
            td 3-5 páginas
          tr.bg-white
            td Conclusiones
            td Interpretaciones y recomendaciones
            td Gerencia y equipo técnico
            td Medio - síntesis técnica
            td 2-3 páginas
          tr.bg-white
            td Anexos técnicos
            td Código, logs y documentación adicional
            td Equipo técnico
            td Muy alto - detalles completos
            td Sin límite
    
    .row.justify-content-center.mb-2(data-aos="flip-up")
      .col-lg-10
        .fondo-color-sistema-j.p-2
          .row.align-items-center
            .col-md-auto
              figure.mb-4.mb-md-0
                img.mx-auto(src="@/assets/curso/tema2/3.svg",style="max-width: 90px;")
            .col
              p.mb-0 Esta estructura proporciona un marco de referencia que puede adaptarse según las necesidades específicas del proyecto y la organización, manteniendo siempre un flujo lógico y coherente de información.
    
    Separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.2 Metodologías de documentación
    
    p.mb-4(data-aos="fade-right") Las metodologías de documentación para informes técnicos avanzados han evolucionado para adaptarse a las necesidades de proyectos de datos cada vez más complejos. El enfoque modular permite desarrollar secciones independientes que luego se integran en un documento cohesivo, facilitando la colaboración entre diferentes equipos y especialistas.
    p.mb-5(data-aos="fade-left") La creación de informes técnicos sigue un proceso iterativo que involucra múltiples etapas y participantes. La siguiente infografía ilustra el flujo de trabajo típico en la generación de informes técnicos avanzados, desde la recopilación inicial de información hasta la publicación final.

    .row.justify-content-center.mb-4(data-aos="fade")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          p.mb-0 #[b Figura 1.] Ciclo de vida del informe técnico
        
        figure.mb-2
          img.mx-auto(src="@/assets/curso/tema2/4.svg",style="max-width: 505px;")
        figcaption.fw-normal #[em #[b Fuente]: OIT, 2024.]
    
    .row.justify-content-center.mb-3(data-aos="flip-up")
      .col-lg-10
        .fondo-color-sistema-j.p-2
          .row.align-items-center
            .col-md-auto
              figure.mb-4.mb-md-0
                img.mx-auto(src="@/assets/curso/tema2/5.svg",style="max-width: 90px;")
            .col
              p.mb-0 El diagrama representa las etapas interconectadas del proceso de documentación, destacando los puntos de revisión, validación y retroalimentación. Esta visualización ayuda a comprender cómo cada fase contribuye a la calidad final del informe, donde los diferentes roles interactúan durante el proceso.
    
    Separador

    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.3 Gestión de versiones
    
    p.mb-4(data-aos="fade-up") La gestión de versiones en informes técnicos trasciende el simple control de cambios. Implica mantener un registro detallado de la evolución del documento, las decisiones tomadas y las modificaciones realizadas. Esta práctica resulta especialmente importante en entornos colaborativos donde múltiples autores contribuyen al documento.

    .row.align-items-center
      .col-lg-7(data-aos="fade-right")
        p.mb-4 Los sistemas modernos de control de versiones permiten mantener un historial completo de cambios, facilitando la trazabilidad y la capacidad de revertir modificaciones cuando sea necesario. La integración con sistemas de gestión de código permite vincular versiones específicas del informe con los conjuntos de datos y análisis correspondientes.

        .fondo-color-sistema-k.p-4.mb-4
          p.mb-0 El versionado semántico (#[em Semantic Versioning]) ha emergido como un estándar efectivo para la numeración de versiones de informes técnicos. Este sistema utiliza tres números (MAYOR. MENOR. PARCHE) para indicar la naturaleza de los cambios realizados, facilitando la comprensión rápida del impacto de cada actualización.
        
        p.mb-0 La documentación de cambios entre versiones debe incluir no solo qué se modificó, sino también por qué se realizaron los cambios. Esta información contextual resulta invaluable para comprender la evolución del análisis y las decisiones tomadas en diferentes momentos del proyecto.

      .col-lg-5.order-first.order-lg-last(data-aos="fade-left")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema2/6.svg",style="max-width: 393px;")


</template>

<script>
import SlyderA from '../bootstrap/SlyderA.vue'
export default {
  name: 'Tema2',
  components: {
    SlyderA,
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
