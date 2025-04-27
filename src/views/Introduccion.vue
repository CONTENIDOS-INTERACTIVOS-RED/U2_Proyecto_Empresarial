<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/intro/1.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-5.p-4(data-aos="fade-left").mb-4
          p.mb-0 En el entorno empresarial actual, la evaluación del impacto y la mejora continua se han convertido en elementos clave para garantizar el éxito y la sostenibilidad de las organizaciones. La capacidad de medir el impacto de un proyecto en términos sociales, ambientales y económicos permite a las empresas tomar decisiones fundamentadas y alinear sus estrategias con principios de responsabilidad y eficiencia. En este contexto, se explorarán herramientas y metodologías que faciliten la evaluación de resultados, fomentando una gestión más transparente y efectiva.
        p(data-aos="fade-left").mb-4 Al finalizar esta unidad, se espera que los estudiantes sean capaces de analizar y evaluar los resultados de un proyecto, diseñar propuestas concretas de mejora continua y comprender cómo la evaluación de impacto influye en la toma de decisiones y la cultura organizacional. Estos conocimientos les permitirán desarrollar habilidades esenciales para gestionar iniciativas empresariales alineadas con estándares de sostenibilidad y rentabilidad a largo plazo.

    .bg-full-width.image-out-bg.mb-5
      .px-4.px-md-5
        .row.align-items-center

          .col-lg
            .pt-4
              p.mb-3.text-white La importancia del liderazgo ético y la responsabilidad social empresarial (RSE) también se abordará como parte fundamental de la gestión organizacional. Se explorará cómo la implementación de buenas prácticas en RSE puede mejorar la reputación corporativa, fortalecer la relación con stakeholders y generar beneficios tanto para la empresa como para la comunidad en la que opera. Asimismo, se analizará la evolución de la RSE y su impacto en el bienestar de los empleados, la innovación sostenible y la rentabilidad empresarial. 3

          .col-lg-auto
            img(src="@/assets/curso/intro/2.svg", style="max-width: 400px").mx-auto

  
</template>
<style lang="sass">
.image-out-bg
  position: relative
  &::after
    content: ''
    position: absolute
    bottom: 0%
    left: 0
    width: 100%
    height: 85%
    transform: translateY(-0%)
    background-color: #103D47
    z-index: 0
  .col-lg-auto, .col-lg, .row
    z-index: 1


  @media screen and (max-width: bp-max-md)
    padding: 1rem

    &::after
      height: 100%
</style>
