<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1  Escenarios de riesgo
    
    
    .row.container.justify-content-around.align-items-center
        figure
              img(src="@/assets/curso/temas/img-sup-dertema2.png").img-sup-dertema2
        
        .col-4
            figure
              img(data-aos="fade-up")(src="@/assets/curso/temas/ing1-corr-tema2.png").img1-tema2

        .col-8.color-fondo-tarj1.tarjeta
            .row 
              .col-lg-2 
                figure
                  img(src="@/assets/curso/temas/img-fondo-der-tarj1-tema1.png").img-fondo-der-tarj1-tema1
              .col-lg-4
                p.text-tarj1-color.p-3 Para desarrollar la gestión y ejecutar medidas de reducción de riesgo de desastres, se requiere la selección de herramientas para la planificación.
                  br
                  br
                  |Esta selección debe cumplir con criterios y mecanismos establecidos, que aseguren la efectividad, la pertinencia y la oportunidad en los procesos.
                  br
                  br
                  |Una vez reconocidos los instrumentos de planificación, le invitamos a ver en el siguiente video, elementos a considerar sobre los escenarios de riesgo.
              
            .col-lg-2
                figure
                  img(src="@/assets/curso/temas/img-fondo-izq-tarj1-tema1.png").img-fondo-izq-tarj1-tema1
      
    br  
    br  
    br

    .row.container.tarjeta.tarjeta--blanca.p-2.p-md-3


        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/Fu2U2W252yE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    br                  
    br                  
    br

    .row.container.tarjeta.tarjeta--blanca.p-2.p-md-3
      h3 Metodologías de caracterización y priorización
      
      br
      br
      
      p En relación con los escenarios de riesgo, es fundamental la identificación de las metodologías de caracterización y priorización, tal como se presenta a continuación:
      
      figure
          img(src="@/assets/curso/temas/img-izq-tema2.png", alt="alt").img-izq-tema2
      
      .bg--img_03
          .row.justify-content-center.mb-4
            
            .col-lg-8
              AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
                .row(titulo="Ley 1523 de 2012 - Primera parte")
                  .col-12
                    p.texto-acordeon-tema1 El artículo 39 de la Ley 1523 de 2012 contempla la integración de la Gestión del Riesgo de Desastres en la planificación territorial y del desarrollo, con base en esto, el Programa de Naciones Unidas para el Desarrollo Colombia (PNUD) y la Unidad Nacional de Gestión del Riesgo de Desastres (UNGRD) consolidaron un instrumento técnico que sirve como directriz para la incorporación de la gestión del riesgo a nivel local: <em>la Guía metodológica para la elaboración de planes departamentales para la gestión del riesgo.</em>

                .row(titulo="Ley 1523 de 2012 - Segunda parte")
                  .col-12
                    p.texto-acordeon-tema1 En esta directriz se instruye a las instituciones públicas acerca de los lineamientos para la identificación, ejecución y control de las acciones que los entes territoriales hacen en términos de los procesos de gestión del riesgo, teniendo como base la caracterización del territorio, factores y escenarios de riesgo, y actores claves para la gestión del riesgo que orientan la implementación de la Estrategia Departamental para Respuesta (Departamento Administrativo del Sistema de Prevención, Atención y Recuperación de Desastres en Antioquia, 2015). 

                .row(titulo="Guía metodológica para la formulación y actualización de Planes Municipales de Gestión del Riesgo de Desastres ")
                  .col-12
                    p.texto-acordeon-tema1 Así mismo, se cuenta con la Guía metodológica para la formulación y actualización de Planes Municipales de Gestión del Riesgo de Desastres (PMGRD) diseñada por la Unidad Nacional para la Gestión del Riesgo de Desastres (UNGRD) en el año 2021.


            .col-lg-4
              figure(data-aos="zoom-in")
                img(src="@/assets/curso/temas/img-acordeon1-tema2.png", alt="alt").img400.m-auto
    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-derecha
          .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
              :style="{'background-image':`url(${require('@/assets/curso/temas/c/c2.jpg')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 De acuerdo con la Unidad Nacional para la Gestión del Riesgo de Desastres (UNGRD), en su publicación Guía metodológica para la formulación y actualización de Planes Municipales de Gestión del Riesgo de Desastres, se articulan seis pasos fundamentales que se deben de tener en cuenta al momento de integrar los procesos de gestión del riesgo, en la planificación territorial (Unidad Nacional para la Gestión del Riesgo de Desastres, 2021). 
                br
                br
                |Estos seis pasos son:
    

    .row.container.tarjeta.tarjeta--blanca.p-2.p-md-3
      
        .row.justify-content-center.mb-5
          .col-lg-5
            figure
              img(src="@/assets/curso/temas/img-pasos-vert-tema2.png", alt="alt")
          .col-lg-7
            LineaTiempoD.color-secundario
              p(numero="1" titulo="Primer paso") Definir la planeación estratégica en función de la GRD. Establecer la misión, la visión y los objetivos respondiendo a la articulación existente con las herramientas de planificación y teniendo como objetivo la ejecución de los procesos y subprocesos de la gestión del riesgo en el marco de la Ley 1523 de 2012.

              p(numero="2" titulo="Segundo paso") Caracterización general del departamento y su entorno. Se realiza en función de dos componentes principales: recopilación de la información y la validación y análisis de la información. Estos dan como resultado el conocimiento del territorio en términos geográficos, socioculturales, económicos, de antecedentes históricos y físicoambientales (fisiografía, geología, geomorfología, hidrografía, variables hidroclimatológicas y zonificación ecológica).

              p(numero="3" titulo="Tercer paso") Desarrollar el autodiagnóstico de acuerdo con la Gestión del Riesgo de Desastres (capacidades). Se lleva a cabo mediante las capacidades mínimas establecidas en el Marco Estratégico para la Gestión del Riesgo de Desastres.

              p(numero="4" titulo="Cuarto paso") Identificación de actores claves. Llevar a cabo un análisis y recopilación de los actores relacionados con los procesos y subprocesos de la gestión del riesgo en los sectores económico, sociocultural, político-administrativo y de índole internacional.

              p(numero="5" titulo="Quinto paso") Identificación de factores de riesgo. Determinar las causas que crean una condición de riesgo: amenaza (natural, antrópica, tecnológica y socionatural) y vulnerabilidad (factores físicos, ambientales, económicos y sociales).

              p(numero="6" titulo="Sexto paso") Identificar y caracterizar los escenarios de riesgo. Se identifican y analizan los escenarios de riesgo, los cuales dan una visión aproximada de los efectos de una amenaza mediante la definición de criterios de frecuencia y magnitud.

        p En lo que se refiere al tercer paso, que tiene que ver con el desarrollo del autodiagnóstico, se presentan nueve preguntas que orientan la formulación del mismo: 

    br
    br
    br

    .row.container.tarjeta.tarjeta--blanca.p-2.p-md-3
        
        .row.fondo-bloque-pto-caliente.p-4
          ImagenInfografica.color-acento-botones
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/temas/img2-pto-caliente-tema2.png', alt='Texto que describa la imagen').img-pto-caliente-tema2
                //figcaption Leyenda de la imagen

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="15%" y="10%" numero="1")
              //.h5.mb-2 titulo
              p ¿Cuál es el estado actual del Consejo Municipal de Gestión del Riesgo de Desastres?

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="11%" y="30%" numero="2")
              //.h5.mb-2 titulo
              p ¿Cuál es el estado actual de la oficina municipal de Gestión del Riesgo de Desastres?

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="11%" y="50%" numero="3")
              //.h5.mb-2 titulo
              p ¿El municipio cuenta con una hoja de ruta para el fortalecimiento de sus capacidades municipales?
          
            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="15%" y="70%" numero="4")
              p ¿La Gestión del Riesgo de Desastres se encuentra integrada en su Plan de Ordenamiento Territorial y en el Plan de Desarrollo Municipal?

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="37%" y="90%" numero="5")
              //.h5.mb-2 titulo
              p ¿El municipio cuenta con una estrategia financiera para la implementación de la Gestión del Riesgo de Desastres?

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="83%" y="70%" numero="6")
              //.h5.mb-2 titulo
              p ¿El municipio cuenta con un sistema de información de Gestión del Riesgo de Desastres para la toma de decisiones?
          
            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="89%" y="50%" numero="7")
              //.h5.mb-2 titulo
              p ¿El municipio cuenta con herramientas y capacidades técnicas clave para la gestión del riesgo?

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="89%" y="30%" numero="8")
              //.h5.mb-2 titulo
              p ¿Cuáles son las capacidades de respuesta y recuperación post-desastre con las que cuenta el municipio?

            .tarjeta.fondo-color-tarj-pto-caliente.p-3(x="82%" y="10%" numero="9")
              //.h5.mb-2 titulo
              p ¿El municipio cuenta con la participación activa de la comunidad y del sector privado en la Gestión del Riesgo de Desastres?
        
        p.txt-inf-pto-caliente-tema2 En lo relacionado con el paso 6, identificación y caracterización de escenarios de riesgo, se describen a continuación ejemplos de escenarios de riesgo, a partir de algunos criterios definidos:


    br
    br
    br

    .tarjeta.p-4(style="background-color: #f6f6f6")
      SlyderF(columnas="col-lg-6 col-xl-4").slyder-100 
        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img1-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por fenómeno amenazante
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Inundaciones
            li 
              i.lista-ul__vineta
              | Sismos
            li 
              i.lista-ul__vineta
              | Incendios estructurales
            li 
              i.lista-ul__vineta
              | Avenidas torrenciales
          
          p.texto-invisible Lorem ipsum dolor sit amet consectetur adipisicing elit.

        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img2-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por tipo de elemento o bien expuesto
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Puentes
            li 
              i.lista-ul__vineta
              | Cultivos
            li 
              i.lista-ul__vineta
              | Viviendas
            li 
              i.lista-ul__vineta
              | Infraestructura esencial
              
          p.texto-invisible Lorem ipsum dolor sit 

        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img3-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por tipos de daños
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Heridos
            li 
              i.lista-ul__vineta
              | Trauma psicológico
            li 
              i.lista-ul__vineta
              | Contaminación de ecosistemas
            li 
              i.lista-ul__vineta
              | Muertes
          
          p.texto-invisible Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis rem 

        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img4-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por grupo social
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Niños y niñas
            li 
              i.lista-ul__vineta
              | Adultos mayores
            li 
              i.lista-ul__vineta
              | Mujeres cabeza de familia
            li 
              i.lista-ul__vineta
              | Indígenas
          p.texto-invisible Lorem ipsum dolor sit amet consectetur adipisicing elit.adipisicing elit.

        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img5-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por actividades económicas
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Minería
            li 
              i.lista-ul__vineta
              | Transporte
            li 
              i.lista-ul__vineta
              | Industria química


        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img6-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por actividades sociales
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Corralejas
            li 
              i.lista-ul__vineta
              | Peregrinaciones multitudinarias

        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img7-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por actividades institucionales
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Instituciones educativas
            li 
              i.lista-ul__vineta
              | Unidades militares

          
        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img8-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo por operaciones de grandes obras
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | Embalses
            li 
              i.lista-ul__vineta
              | Túneles
            li 
              i.lista-ul__vineta
              | Líneas de flujo de hidrocarburos

        .tarjeta.p-4(style="background-color: #c4e4e1").h-100
          .row.justify-content-center.mb-3
            .col-8
              img(data-aos="flip-left")(src='@/assets/curso/temas/img9-carr-tarj-tema2.png' alt='AvatarTop')
          h4.text-center Escenarios de riesgo de origen biológico
          ul.lista-ul
            li 
              i.lista-ul__vineta
              | SARS COVID-19
            li 
              i.lista-ul__vineta
              | Túneles
            li 
              i.lista-ul__vineta
              | Zika

            li 
              i.lista-ul__vineta
              | Chikungunya

            li 
              i.lista-ul__vineta
              | Entre otros


    br   
    br   
    br

    .row.container.tarjeta.tarjeta--blanca.p-2.p-md-3       
        
        .row.fondo-tarj-final-tema2(data-aos="fade-left")
          .col-lg-7
            p.txt-tarj-final-tema2.p-4 Posterior al reconocimiento del territorio, la identificación y caracterización de los escenarios de riesgo, se lleva a cabo la priorización de los escenarios teniendo como criterios la frecuencia y la magnitud. Por frecuencia se entiende cuando, en los antecedentes históricos, se ha materializado en repetidas ocasiones el mismo escenario en el espacio geográfico delimitado. Y, por magnitud, cuando el escenario ocasiona grandes daños en términos de medios de subsistencia y vidas humanas, y genera pérdidas económicas.

          .col-lg-5
              figure
                img(src='@/assets/curso/temas/img-tarj-final-tema2.png', alt='Texto que describa la imagen').img-tarj-final-tema2
              p.texto-invisible Lorem ipsum dolor sit, amet 
          
          figure
              img(src='@/assets/curso/temas/img-inf-izq-tema2.png', alt='Texto que describa la imagen').img-inf-izq-tema2
              


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
