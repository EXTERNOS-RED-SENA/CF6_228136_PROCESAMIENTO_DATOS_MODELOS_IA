<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mb-4
      .col-lg-9(data-aos="fade-right")
        .fondo-color-sistema-i.p-4
          p.mb-4 En la era de los datos masivos, la sistematización y documentación efectiva del conocimiento se ha convertido en un elemento diferenciador para las organizaciones. La capacidad de capturar, organizar y comunicar el conocimiento técnico determina no solo la eficiencia operativa actual, sino también la capacidad de evolución y mejora continua de los sistemas analíticos.
          p.mb-0 Este componente formativo aborda los aspectos fundamentales de la documentación y sistematización de datos masivos, proporcionando un marco integral para la gestión del conocimiento técnico. Desde la creación de documentación robusta hasta la implementación de sistemas de gestión del conocimiento, cada tema se explora con un enfoque práctico y orientado a resultados.
      .col-lg-3.order-first.order-lg-last(data-aos="fade-left")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema1/1.png",style="max-width: 295px;")
    
    .row
      .col-lg-5(data-aos="fade-right")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/tema1/2.png",style="max-width: 528px;")
      .col-lg-7
        p.mb-4(data-aos="fade") La documentación técnica moderna trasciende la simple recopilación de información, convirtiéndose en un activo estratégico que facilita la colaboración, el mantenimiento y la evolución de los sistemas de datos. Las metodologías y herramientas presentadas reflejan las mejores prácticas actuales en la industria, adaptadas a las necesidades específicas de proyectos de datos masivos.
        p.mb-4 Como suele decirse en el campo de la gestión del conocimiento: "La información solo se convierte en conocimiento cuando está documentada, accesible y puede ser aplicada". Este principio guiará nuestra exploración de las técnicas y metodologías presentadas en este componente.
        
        .fondo-color-sistema-j.p-2.px-3.text-center
          p.mb-0(data-aos="fade") ¡Bienvenido al mundo de la sistematización y documentación efectiva de datos masivos!
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
