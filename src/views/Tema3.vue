<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Características físicas y químicas del agua en proceso de potabilización

    p.mb-5(data-aos="fade-left") El agua cruda posee características fisicoquímicas que pueden incidir directamente en el proceso de potabilización, así como en la elección de los insumos químicos necesarios para su tratamiento.

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 <b>Agua cruda</b>: se refiere al agua que no ha recibido ningún tipo de tratamiento para su consumo. Proviene de fuentes superficiales, estancadas o subterráneas y se utiliza sin pasar por procesos de purificación.

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        .bg-full-width.bg-color-4.mb-5
          .px-4.px-md-5.py-4
            p.mb-0 A continuación, se presenta un video sobre las características del agua cruda, sus parámetros físicos y químicos, y los desafíos que implica su tratamiento para el consumo humano.
    
    figure(data-aos="fade-left")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/SxGIwxrVkfE?si=_jDkmaTIR7EDEylT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Tema3',
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
