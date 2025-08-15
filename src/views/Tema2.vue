<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Tipos de plantas de tratamiento de agua
    
    .row.mb-4.align-items-center.mb-5
      .col-lg-9.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").mb-4
          p.mb-0 El tipo de planta de tratamiento de agua potable y sus procesos unitarios dependen de la calidad del agua cruda, cuando el agua proviene de fuentes hídricas con altos niveles de contaminación, la planta puede necesitar procesos más complejos, también cuando el agua presenta pH bajos o altas concentraciones de hierro, se requieren unidades adicionales como aireadores y adición de sustancias químicas para remoción o estabilización para que los procesos de coagulación floculación se puedan dar sin inconvenientes. Los tipos de plantas de tratamiento de agua potable (PTAP) se describen a continuación:
      .col-lg-3
        figure
          img(src="@/assets/curso/temas/tema2/1.png", data-aos="zoom-in", style="max-width: 450px").m-auto
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Planta de tratamiento de agua potable de tipo convencional
    
    p(data-aos="fade-left") Este tipo de PTAP contienen unidades de coagulación floculación, sedimentación y filtración convencional para remoción de color, turbidez y microorganismos, generalmente no requieren unidades adicionales.
    p(data-aos="fade-left") La  figura 1 representa el tipo de planta convencional, donde pueden encontrarse las operaciones unitarias tales como el punto de mezcla rápida donde se adiciona el coagulante e inicia la reacción química, luego se encuentra la unidad de floculación donde se aglutinan los sólidos suspendidos e inicia la clarificación del agua, los sólidos mas pesados se quedarán en esta unidad, posteriormente el agua ingresa a la unidad de sedimentación donde las partículas deben quedar en el fondo y es aquí donde el agua ya presenta un bajo nivel de turbiedad e ingresa a la unidad de filtración donde en el lecho compuesto por materiales como grava, gravilla y antracita, se retienen las partículas mas finas y el agua puede pasar a ser desinfectada, ya sea mediante la inyección de cloro gaseoso o aplicación por goteo de solución de cloro, finalmente el agua es almacenada en el tanque de contacto para ser distribuida a los usuarios del sistema de acueducto. 

    .bg-full-width.bg-color-3.mb-0.mb-lg-4
      .p-4.py-lg-0.px-4.px-md-5
        .row.justify-content-center
          .col-12
            .titulo-sexto.color-acento-contenido(data-aos="fade-right")
              h5 Figura 1.
              span Diagrama planta de tratamiento de agua potable de tipo convencional
            
            figure.mb-5(data-aos="zoom-in")
              img(src="@/assets/curso/temas/tema2/2.svg", data-aos="zoom-in", alt="El esquema representa los procesos unitarios de una planta de tratamiento de agua potable de tipo convencional.").mb-4.mb-lg-0
              figcaption Nota.  Romero (1999).
        
        .titulo-con-imagen.my-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
            h3.titulo-con-imagen__texto Planta para suministro pequeño con agua cruda de buena calidad
        
        p(data-aos="fade-left") Cuando la fuente abastecedora tiene agua cruda con bajos niveles de turbiedad y poca contaminación, es posible instalar o construir plantas de tratamiento con unidades de sedimentación, filtración y desinfección.
        p(data-aos="fade-left") Este tipo de plantas, tal como se muestra en el esquema de la figura 2, se compone básicamente de unidad de sedimentación, esto debido a que la calidad del agua cruda presenta concentraciones de turbiedad relativamente bajas, requiriéndose en la planta solo la unidad de sedimentación para remover los sólidos que trae el agua, posteriormente se realiza la filtración para remover partícula que no son detectables al ojo humano y finalmente al igual que en la planta convencional se realiza el proceso de desinfección y almacenamiento.

        .row.justify-content-center
          .col-12
            .titulo-sexto.color-acento-contenido(data-aos="fade-right")
              h5 Figura 2.
              span Diagrama planta para suministro pequeño con agua cruda de buena calidad
            
            figure.mb-5(data-aos="zoom-in")
              img(src="@/assets/curso/temas/tema2/3.svg", data-aos="zoom-in", alt="El esquema muestra las unidades que componen una planta para suministro pequeño con agua cruda de buena calidad, lo cual permite reducir algunos procesos como la floculación.").mb-4.mb-lg-0
              figcaption Nota.  Romero (1999).
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Plantas de ablandamiento
    
    .row.mb-4.align-items-center
      .col-lg-8.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").mb-4
          p Cuando se presentan aguas con alta concentración de dureza (alta concentración de calcio y magnesio), se requieren plantas de tratamiento con unidad de ablandamiento, en la cual se busca reducir la dureza del agua para evitar afectaciones a la salud humana y además impedir que se formen incrustaciones en las tuberías. En este tipo de plantas puede darse la necesidad de adicionar productos como cal u otros productos químicos que hacen más complejo el tratamiento. En los dos diagramas que se encuentran a continuación puede observarse las unidades de tratamiento y los productos que deben adicionarse para que los procesos de coagulación floculación y sedimentación se pueden desarrollar de manera óptima.
          p.mb-0 La figura 3 hace referencia a una planta de tratamiento donde debido a la concentración de pH, que puede estar por debajo de las 5 unidades, es necesario aplicar previamente al coagulante, otro insumo como lo es la cal, esto con el fin de estabilizar el pH y que el proceso de floculación se dé satisfactoriamente, adicionalmente puede ser necesario aplicar también carbonato de sodio, (soda ASH) para tener también un control de la dureza del agua. Cuando en el tratamiento previo (coagulación, desinfección o ablandamiento con cal) el pH del agua queda demasiado alto, por tanto, una de las operaciones posibles es la inyección de CO₂ para reducirlo y finalmente proceder con la filtración.
      .col-lg-4
        figure
          img(src="@/assets/curso/temas/tema2/4.png", data-aos="zoom-in", style="max-width: 450px").m-auto
    
    .bg-full-width.bg-color-3.mb-5
      .p-4.py-lg-0.px-4.px-md-5
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Figura 3.
          span Diagrama planta de ablandamiento con doble mezcla rápida
        
        figure.mb-5(data-aos="zoom-in")
          img(src="@/assets/curso/temas/tema2/5.svg", data-aos="zoom-in", alt="El diagrama muestra los procesos unitarios de una planta que requiere proceso de ablandamiento o disminución de la dureza del agua, en este caso puede requerirse doble punto de mezcla rápida.").mb-4.mb-lg-0
          figcaption Nota.  Romero (1999).

        p.mb-5(data-aos="fade-left") A diferencia de la planta presentada en el esquema anterior, el tipo de planta que se muestra en la figura 4, indica que en el punto de mezcla rápida se aplican los dos insumos como lo son la cal y la Soda ASH, esto puede influir en que el pH del agua al llegar a la unidad de filtración pueda estar muy elevado, por lo tanto se aplica el CO2 para regular el pH y proceder con la desinfección y además garantizar que los parámetros de calidad de agua para consumo humano cumplan con la normativa vigente.
        
        .row.justify-content-center
          .col-12
            .titulo-sexto.color-acento-contenido(data-aos="fade-right")
              h5 Figura 4.
              span Diagrama planta de ablandamiento con una unidad de mezcla rápida
            
            figure.mb-5(data-aos="zoom-in")
              img(src="@/assets/curso/temas/tema2/6.svg", data-aos="zoom-in", alt="El diagrama representa los proceso de una de ablandamiento, donde se requiere adición de productos como la cal, que además contribuye a estabilizar el pH del agua.").mb-4.mb-lg-0
              figcaption Nota.  Romero (1999).

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Plantas de remoción de hierro y magnesio

    .row.mb-4.align-items-center
      .col-lg-8.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").mb-4
          p Son sistemas diseñados para remover metales del agua, regularmente se construyen o implementar cuando la fuente abastecedora es de agua subterránea, este tipo de fuentes se caracterizan por presentar altos contenidos de metales como el hierro, que puede dar altos niveles de color que puede afectar los sistemas de tuberías y la salud humana, por ello se requiere contar plantas que garanticen la remoción de metales.
          p.mb-0 El tipo de planta de la figura 5 puede ser implementada cuando el agua cruda tiene altas concentraciones de hierro y magnesio, esto podría darse cuando el agua cruda es extraída de pozos subterráneos, en este caso se aplica un oxidante químico (por ejemplo, el Permanganato de potasio) con el fin de que se logren retener estos elementos y los demás procesos unitarios se den de manera óptima, finalizando en este caso con la desinfección con cloro.
      .col-lg-4
        figure
          img(src="@/assets/curso/temas/tema2/7.png", data-aos="zoom-in", style="max-width: 450px").m-auto.mb-4.mb-lg-0
    
    .bg-full-width.bg-color-3
      .p-4.py-lg-0.px-4.px-md-5
        .row.justify-content-center
          .col-12
            .titulo-sexto.color-acento-contenido(data-aos="fade-right")
              h5 Figura 5.
              span Diagrama planta de remoción de hierro y magnesio
            
            figure.mb-5(data-aos="zoom-in")
              img(src="@/assets/curso/temas/tema2/8.svg", data-aos="zoom-in", alt="El esquema muestra los procesos unitarios que puede tener una planta donde el agua druda presenta altos contenidos de hierro y magnesio, por lo cual se necesita ajuste de pH y adición de oxidante químico.").mb-4.mb-lg-0
              figcaption Nota.  Romero (1999).

        p.mb-5(data-aos="fade-left") La figura 6 representa un tipo de planta donde la carga microbiológica, además de la concentración de hierro y magnesio son altas, por lo general el agua cruda presenta olores característicos de estos elementos, para estos casos una operación recomendada es la aireación, la cual contribuye con la remoción de olores y altas concentraciones de hierro, dependiendo del caudal a tratar la unidad de aireación puede ser parte integral con las demás unidades o en otros casos se encuentra como unidad independiente antes de ingresar el agua a las unidades de la planta de tratamiento de agua potable. En este caso, al ingreso y al iniciar proceso de sedimentación se aplica cloro buscando remover gradualmente la carga microbiológica que trae el agua cruda.
        
        .row.justify-content-center
          .col-12
            .titulo-sexto.color-acento-contenido(data-aos="fade-right")
              h5 Figura 6.
              span Diagrama planta de remoción de hierro y magnesio con aireación
            
            figure(data-aos="zoom-in")
              img(src="@/assets/curso/temas/tema2/9.svg", data-aos="zoom-in", alt="El diagrama muestra una planta donde el agua a tratar contiene hierro y magnesio, en este caso se encuentran varios puntos de cloración.").mb-4.mb-lg-0
              figcaption Nota.  Romero (1999).

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
