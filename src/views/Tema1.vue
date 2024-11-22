<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Documentación técnica
    
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-2(data-aos="flip-up" data-aos-duration="1000")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La documentación técnica representa un elemento fundamental en la gestión de datos masivos y analítica. Más allá de un simple registro de procedimientos, constituye la memoria institucional de los procesos de datos, facilitando la reproducibilidad, el mantenimiento y la transferencia de conocimiento. Este capítulo explora los diferentes tipos de documentación, estándares actuales y herramientas que facilitan esta labor esencial.
    
    Separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.1 Tipos de documentación

    p.mb-4(data-aos="fade-right") La documentación técnica en el contexto de datos masivos abarca diversos niveles y propósitos. Los documentos de arquitectura proporcionan una visión general de la estructura y flujo de datos, mientras que la documentación de procesos detalla los pasos específicos en las transformaciones y análisis. Los manuales de usuario y las guías de mantenimiento completan el espectro, asegurando que todos los #[em stakeholders] puedan interactuar efectivamente con los sistemas de datos.

    p.mb-5(data-aos="fade-up") Para comprender mejor los diferentes tipos de documentación y sus características específicas, consideremos la siguiente clasificación detallada:

    .titulo-sexto.color-acento-contenido(data-aos="fade-up")
      p.mb-0 #[b Tabla 1.] Tipos de documentación y características
    
    .tabla-a.color-primario.mb-4(data-aos="fade-up")
      table
        caption.fw-normal #[strong Fuente.] OIT, 2024.
        thead
          tr.text-white.text-center(style="background-color:#03A9F4;")
            th Tipo de documentación
            th Audiencia principal
            th Contenido clave
            th Frecuencia de actualización
            th Nivel de detalle
        tbody.text-center
          tr.bg-white
            td Arquitectura de datos
            td Arquitectos, Ingenieros
            td Diagramas de flujo, modelos de datos, dependencias
            td Baja - en cambios mayores
            td Alto nivel, enfoque en relaciones
          tr.bg-white
            td Procesos ETL
            td Desarrolladores, Analistas
            td Transformaciones, reglas de negocio, validaciones
            td Media - con cada modificación
            td Detallado, paso a paso
          tr.bg-white
            td APIs e interfaces
            td Desarrolladores externos e internos
            td #[em Endpoints], parámetros, ejemplos de uso
            td Alta - con cada cambio de API
            td Técnico y específico
          tr.bg-white
            td Calidad de datos
            td Analistas, Gestores de datos
            td Métricas, umbrales, procedimientos de validación
            td Alta - seguimiento continuo
            td Medio, énfasis en métricas
          tr.bg-white
            td Seguridad y acceso
            td Administradores, Auditores
            td Políticas, permisos, protocolos
            td Media - cambios en políticas
            td Exhaustivo en procedimientos
          tr.bg-white
            td Guías de usuario
            td Usuarios finales
            td Instrucciones de uso, casos comunes, solución de problemas
            td Media - nuevas funcionalidades
            td Básico, enfoque práctico
    
    .row.justify-content-center.mb-2(data-aos="zoom-in-out")
      .col-lg-10
        .fondo-color-sistema-j.p-4.px-lg-5
          p.mb-0 Esta clasificación permite alinear cada tipo de documentación con sus objetivos específicos y audiencia prevista, facilitando la creación y mantenimiento de una estructura documental coherente y efectiva.
    
    Separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 1.2 Estándares y mejores prácticas

    .row.mb-4
      .col-lg-7
        p.mb-4(data-aos="fade-left") Los estándares de documentación técnica han evolucionado significativamente con la expansión de los sistemas de datos masivos. La adopción de formatos estandarizados como Markdown o AsciiDoc facilita la creación y mantenimiento de documentación que puede versionarse junto con el código. La documentación como código (#[em Documentation as Code]) ha emergido como un paradigma que permite tratar los documentos técnicos con el mismo rigor y herramientas que el código fuente.
        p.mb-0(data-aos="fade-right") Las mejores prácticas actuales enfatizan la importancia de la documentación viva, que evoluciona junto con los sistemas que describe. Esto implica integrar la documentación en el ciclo de desarrollo, estableciendo procesos de revisión y actualización regulares. La automatización juega un papel importante, permitiendo generar parte de la documentación directamente desde el código y los metadatos del sistema.
      .col-lg-5.order-first.order-lg-last(data-aos="fade")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema1/4.png",style="max-width: 505px;")
    
    .row.justify-content-center.mb-2(data-aos="flip-up")
      .col-lg-10
        .fondo-color-sistema-j.p-4
          p.mb-0 La consistencia en el estilo y formato resulta esencial para la usabilidad de la documentación. El uso de plantillas predefinidas y guías de estilo ayuda a mantener la coherencia a través de diferentes equipos y proyectos. La documentación debe ser concisa pero completa, evitando tanto la sobrecarga de información como las omisiones significativas.
    
    Separador

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 1.3 Herramientas de documentación
    
    p.mb-4 (data-aos="fade-right")El ecosistema de herramientas para documentación técnica se ha expandido considerablemente en los últimos años. Los sistemas modernos de documentación combinan capacidades de edición colaborativa, control de versiones y publicación automatizada. Herramientas como Sphinx, MkDocs y Confluence han establecido nuevos estándares en la creación y mantenimiento de documentación técnica.

    .row
      .col-lg-5(data-aos="fade-right")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema1/5.svg",style="max-width: 505px;")
      .col-lg-7
        p.mb-4(data-aos="fade-right") La integración con sistemas de control de versiones como Git permite mantener la documentación sincronizada con el código y los procesos que describe. Los sistemas de integración continua pueden automatizar la validación y publicación de documentación, asegurando que los cambios en el código se reflejen adecuadamente en la documentación correspondiente.
        .fondo-color-sistema-k.p-4.mb-4(data-aos="flip-up")
          .row
            .col-md-auto
              figure.mb-4.mb-md-0
                img.mx-auto(src="@/assets/curso/tema1/6.svg",style="max-width: 85px;")
            .col
              p.mb-0 Las herramientas de documentación API, como Swagger o OpenAPI, facilitan la creación y mantenimiento de documentación específica para interfaces de programación. Estas herramientas pueden generar automáticamente documentación actualizada a partir de las definiciones de API, reduciendo el riesgo de discrepancias entre la implementación y la documentación.
        p.mb-0(data-aos="fade") La selección de herramientas debe considerar factores como la escalabilidad, la facilidad de uso para los contribuyentes, las capacidades de búsqueda y la integración con flujos de trabajo existentes. La adopción de herramientas que soportan formatos estándar y exportación a múltiples formatos aumenta la flexibilidad y longevidad de la documentación.

    
    
</template>

<script>
import SlyderA from '../bootstrap/SlyderA.vue'
import AcordionA from '../bootstrap/AcordionA.vue'
export default {
  name: 'Tema1',
  components: {
    SlyderA,
    AcordionA,
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
