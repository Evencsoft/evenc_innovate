<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 1
      h1 Técnicas de Recolección de Información
    .row
      .col-xl-12
        p(data-aos="fade-down") La base fundamental en todo proyecto informático, especialmente en el campo del desarrollo de #[i software], es la información inicial del cliente, mejor conocido como los requerimientos. Para poder acceder a dicha información, debemos recolectar los datos que se necesiten, lo cual podemos definir como el uso de distintas y diversas técnicas y herramientas que tienen disponibles analistas, desarrolladores, etc. para ser utilizadas en los sistemas de información. Específicamente en el campo del desarrollo de #[i software], las más utilizadas y que más se ajustan a nuestras necesidades son: entrevistas, encuestas, cuestionarios, observación y #[i focus gruop]. Los instrumentos mencionados se deben aplicar con el propósito de obtener la información necesaria para comenzar el proyecto.
    
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.1 Sistema extensivo 
     
    .row
      .col-xl-12
        p(data-aos="fade-down") 
          h3(data-aos="fade-down") Entrevistas

    p(data-aos="fade-down").mb-5 Como aspecto principal, es necesario explicar en qué consiste la entrevista teniendo en cuenta que a través de ella se presenta un intercambio de opiniones por medio de un diálogo entre 2 o más personas.
    
    .row.mb-4.mb-md-5(data-aos="fade-down")
      .bg4
      .row.justify-content-center.align-items-center.mb-5           
        .col-lg-10
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/tema1/img1.svg', alt='')
    
    .row.mb-4.mb-md-5(data-aos="fade-down")
      p(data-aos="fade-down").mb-5 Se presentan a continuación tips a tener en cuenta al momento de realizar la entrevista.
    TabsA.color-acento-botones
      .tarjeta.color-acento-botones--borde.p-4(titulo="Preparar el cuestionario")
        h4 Preparar el cuestionario
        .row          
          .col-xl-8
            p Determinante tener claro cuáles son sus objetivos para que, basados en ellos, se tengas los insumos necesarios para obtener mejores y más completas respuestas.
          .col-xl-4.mb-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/tema1/img2.png', alt='')


      .tarjeta.color-acento-botones--borde.p-4(titulo="Decidir el lugar de la entrevista")
        h4 Decidir el lugar de la entrevista
        .row          
          .col-xl-8
            p Aunque actualmente se utilizan mucho las tecnologías de la información y las comunicaciones (TIC), sigue siendo fácil hacer una entrevista presencial para obtener los datos correctos y requeridos. En caso  de que no se pueda, se realiza una entrevista virtual para obtener los mismos resultados.
          .col-xl-4.mb-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/tema1/img2.png', alt='')
      
      .tarjeta.color-acento-botones--borde.p-4(titulo="Hacer sentir cómodo y con confianza al entrevistado")
        h4 Hacer sentir cómodo y con confianza al entrevistado
        .row
          .col-xl-8
            p El entrevistado se siente cómodo, sus respuestas serán más sinceras y precisas, lo cual repercute en el logro de objetivos.      
          .col-xl-4.mb-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/tema1/img2.png', alt='')

    .row.mb-4.mb-md5.my-5(data-aos="fade down") ¿Cuáles son los tipos de preguntas que podemos utilizar para una entrevista?    
    
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .bg_img_01
      .row.justify-content-center.mb-5
        .col-sm-6.col-lg-5.mb-4.mb-lg-0
          .tarjeta--boton.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-4
                .bottomCircle.mb-3
                  figure(data-aos="zoom-in")
                    img(src='@/assets/curso/temas/tema1/img3.png', alt='').img4.m-auto

            h3.text-center Abiertas
            p.text-small Son las que requieren de una mayor descripción y/o explicación; es decir, las que, para dar una respuesta, demandan mayor oratoria. Esto hace que sean sumamente eficaces y efectivas, más completas y de mayor utilidad, incluso, sirven de punto de partida para una nueva pregunta y, por ende, fluye la conversación con el entrevistado.

        .col-sm-6.col-lg-5.mb-4.mb-lg-0
          .tarjeta--boton.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-4
                .bottomCircle.mb-3
                  figure(data-aos="zoom-in")
                    img(src='@/assets/curso/temas/tema1/img3.png', alt='').img4.m-auto

            h3.text-center Cerradas
            p.text-small Son las que limitan las respuestas del entrevistado, son breves, basta un simple sí o no. Sin embargo, pueden ser para proporcionar un dato especifico, pero limitando su respuesta, por ejemplo, la clásica pregunta para seleccionar una opción dentro de unas posibilidades. Este tipo de preguntas son más utilizadas en las encuestas.
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row
      .col-xl-12
        p(data-aos="fade-down") 
          h3(data-aos="fade-down") Cuestionarios
    
    .row.justify-content-center.align-items-center.mb-5
      .col-xl-10
        .bloque-texto-g.color-bloque.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img5.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El cuestionario es un documento compuesto por una serie de preguntas coherentes, muy bien organizadas tanto en secuencia como en estructura, que parte de una planificación específica, esperando obtener respuestas que despejen las dudas planteadas. Los cuestionarios dan la posibilidad de un análisis más detallado, determinar comportamientos, tendencias y posturas. Si bien es cierto que son utilizados en todas las áreas del saber, en los proyectos de desarrollo de software, cumplen con una función sobresaliente. Aunque es innegable su ahorro de tiempo, sus respuestas cortas, los pueden hacer ver como incompletos.    

    .row
      .col-xl-12
        p(data-aos="fade-down") 
          h3(data-aos="fade-down") Encuestas
      
    .row.justify-content-center.align-items-center.mb-5
      .col-xl-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img6.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 De acuerdo con el portal web HubSpot (2022), “una encuesta es un método de investigación que recopila información, datos y comentarios por medio de una serie de preguntas específicas. La mayoría de las encuestas se realizan con la intención de hacer suposiciones sobre una población, grupo referencial o muestra representativa”.
    
    Separador
    .row
      .col-xl-12        
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.2 Observación directa
    .row.justify.content-center.align-items-center
      .col-xl-4
        figure(data-aos="zoom-in")
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/tema1/img7.png', alt='')
      .col-xl-8
        p(data-aos="fade-down") La observación directa consiste principalmente en prestar atención al proceso a sistematizar en su quehacer diario; es decir, como se realiza normalmente una actividad. No obstante, es necesario advertir que el observador no puede participar de ninguna forma en este proceso, de lo contrario, los datos que se obtengan no van a ser válidos.  Otra característica que debemos recalcar en la observación directa es su larga duración, principalmente para garantizar que los individuos que participan en el proceso se acomoden y, por consiguiente, actúen de forma natural, además, para poder obtener la información necesaria y completa del proceso observado.
    
    Separador
    .row
      .col-xl-12       
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.3 #[i Focus Group]
    
    .row.justify-content-center.align-items-center.mb-5
      .col-xl-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img8.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La definición normal de #[i Focus Group] nos dice que es un método de investigación cualitativa, en la que se reúnen una serie de participantes de una entrevista, para expresar sus opiniones acerca de un producto o servicio. Ya específicamente, en el ámbito del desarrollo de software, se aplica como método muy útil que nos ayuda a estudiar propuestas teóricas a partir del juicio de personas expertas y no tan expertas que, basados en su experiencia, aceptan o niegan propuestas de proyectos.
    .row
      .col-xl-12
        p(data-aos="fade-down") El focus group, al ser un grupo pequeño de participantes, se pueden presentar los siguientes roles:
    
    .row.justify-content-center.align-items-center
      .col-lg-10
        ImagenInfografica.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema1/img9.svg', alt='')


          .tarjeta.color-acento-contenido.p-3(x="12%" y="45%" numero="1")
            .row.justify-content-evenly.align-items-center.mb-3           
              .col-9     
                .h5.mb-0 Moderador
              .col-auto.d-none.d-lg-block
                .bulletNumber
            p Integrante del grupo investigador que administra y/o coordina la reunión-discusión debe tener el suficiente tacto y cuidado para no opinar, ni mucho menos influenciar la postura de los demás participantes; además, tiene la tarea de controlar la reunión para evitar que se salga de contexto y esté centrada en los objetivos marcados.

          .tarjeta.color-acento-contenido.p-3(x="68%" y="42%" numero="2")
            .row.justify-content-evenly.align-items-center.mb-3           
              .col-9     
                .h5.mb-0 Relator
              .col-auto.d-none.d-lg-block
                .bulletNumber
            p Integrante del grupo que tiene la función de ejecutar la captura, registro y todos los detalles que genere la reunión en materia de información.

          .tarjeta.color-acento-contenido.p-3(x="78%" y="70%" numero="3")
            .row.justify-content-evenly.align-items-center.mb-3           
              .col-9     
                .h5.mb-0 Grupo Investigador
              .col-auto.d-none.d-lg-block
                .bulletNumber
            p Integrantes del grupo que investigan y abordan una temática específica, con el conocimiento y experiencia suficientes en el tema de estudio y en la aplicación de #[i Focus Group].

          .tarjeta.color-acento-contenido.p-3(x="43%" y="60%" numero="4")
            .row.justify-content-evenly.align-items-center.mb-3           
              .col-9     
                .h5.mb-0 Participantes
              .col-auto.d-none.d-lg-block
                .bulletNumber
            p Integrantes que, basados en su criterio, ejecutan y engrandecen el debate objeto de la reunión, preferiblemente, deben ser expertos en el tema de estudio, puesto que son los que aportan el conocimiento del tema y las mejores formas de aplicación.
    
    .row
      .col-xl-12
        p(data-aos="fade-down") 
          h3(data-aos="fade-down") ¿Cómo organizo un #[i Focus Gruop]?
    
    .row.justify-content-center.align-items-stretch.my-5           
      .col-lg-10.my-3(data-aos="fade-right")        
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/temas/tema1/img10.svg', alt='')
    
    
              
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
