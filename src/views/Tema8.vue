<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 8
      h1 Sustancias para ajuste de pH
    
    .row.mb-4.align-items-center
      .col-lg-9.mb-4.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left")
          p.mb-0 Para que los procesos de coagulación, floculación y sedimentación se desarrollen de manera óptima, el agua cruda debe presentar un pH adecuado. Cuando el pH es inferior a 6, la formación de flóculos se ve comprometida. En estos casos, el producto más utilizado para ajustar el pH es la cal, que puede aplicarse en dos formas:
      .col-lg-3
        figure
          img(src="@/assets/curso/temas/tema8/1.png", data-aos="zoom-in", style="max-width: 450px").m-auto
    
    .row.justify-content-center.mb-5
      .col-lg-8
        .row.justify-content-center
          .col-md-8.col-lg-6.px-0(data-aos="fade-right")
            figure
              img(src='@/assets/curso/temas/tema8/2.png', style="max-width: 450px").m-auto
          .col-md-8.col-lg-6.ps-lg-0(data-aos="fade-left")
            .row.align-items-center.h-100.bg-color-4
              .col-12
                .p-4
                  ul.lista-ul--color.mb-0
                    li.mb-3.d-flex
                      i.fas.fa-circle-check.bg-color-5
                      p.mb-0 Cal viva (CaO)
                    li.mb-3.d-flex.mb-0
                      i.fas.fa-circle-check.bg-color-5
                      p.mb-0 Cal hidratada o apagada (Ca(OH)₂)
    
    p.mb-0(data-aos="fade-right") La cal hidratada es más efectiva en términos de ajuste de pH, aunque requiere una preparación previa y debe almacenarse en forma de lechada antes de su aplicación (Noreña, 2002). La cantidad de cal a dosificar depende de las características específicas del agua a tratar. Si estas se mantienen constantes durante el proceso, el cálculo es más sencillo. Sin embargo, cuando hay variaciones en las propiedades del agua, el operario, con base en su experiencia, estima la cantidad requerida y construye una base de datos que relaciona el volumen de lechada con el ajuste de pH alcanzado. Con esta información, basta conocer el pH de entrada para determinar la cantidad de cal necesaria, la cual se aplica mediante un dosificador que regula el volumen administrado (Noreña, 2002).

</template>

<script>
export default {
  name: 'Tema8',
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
