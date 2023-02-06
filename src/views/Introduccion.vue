<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        .texto-info-intro
          span
            i.fas.fa-info
      h1 Introducción

    .row.container.justify-content-center.align-items-center
      .col-lg-8
        p Apreciado aprendiz, bienvenido a este componente formativo, donde se abordan conceptos y procesos relacionados con la ejecución de acciones en casos de desastres o situaciones de peligro inminente, de acuerdo con la Estrategia de Respuesta a Emergencias (ERE), y en el marco de la competencia de promover acciones de prevención, según normativa y protocolos de gestión del riesgo de desastres.  
          br
          br
          |Potencie sus saberes y habilidades para el uso y gestión de instrumentos de planificación, cuyo objetivo principal es el ordenamiento territorial planificado desde la sostenibilidad; los escenarios de riesgo, que se fundamentan como insumo vital para esta planificación y, por último, las medidas de reducción para la intervención del riesgo.
          br
          br
          |En el siguiente video conocerá, de forma general, la temática que se estudiará a lo largo del componente formativo.
      .col-lg-4: img(src='@/assets/curso/temas/c/c1.jpg', alt='')



    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)


    
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
