<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p.mb-5 El componente formativo el <em>buyer</em> persona según el contexto empresarial se centra en aspectos cruciales para comprender y atraer a los clientes de manera efectiva. Inicia explorando el campo del mercadeo, abordando el <em>marketing</em> en entornos digitales, la planeación estratégica y la segmentación como herramientas clave. Luego, se adentra en la construcción de la propuesta de valor de la organización, utilizando modelos como el de negocio, el Canvas y el ciclo de vida del producto digital. Asimismo, se examinan elementos esenciales como la marca. El componente también profundiza en la elaboración de mapas de empatía, arquetipos digitales y personas compradoras, desglosando sus características distintivas y su papel en la comprensión del cliente, complementado con el concepto de prospecto de cliente y sus atributos.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis del componente formativo el buyer persona según el contexto empresarial se muestran tres temas principales, el mercadeo, la propuesta de valor y los mapas de empatía, arquetipos y buyer persona, que incluyen en sus elementos las estrategias y tácticas clave para comprender y atraer a los clientes de manera efectiva.")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
