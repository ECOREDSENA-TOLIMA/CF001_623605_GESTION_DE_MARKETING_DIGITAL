<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p.mb-5 El <em>buyer</em> persona es un perfil semificticio que simboliza al cliente ideal de una marca porque es construido con base en información demográfica y social de distintos clientes actuales de la empresa, para concretar la personalidad de ese cliente ideal. Tener a los <em>buyer</em> persona claramente definidos es fundamental para cualquier estrategia de <em>marketing</em> digital, ya que facilita la segmentación de clientes y mejora el conocimiento sobre ellos. Lo invitamos a ver el siguiente video para conocer la temática que se abordará en el presente componente formativo.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/wy5koRkNKYM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
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
