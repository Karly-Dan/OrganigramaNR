<template>
  <main>
    <header-principal/>
    <div class="titulo">
      <h1>NUESTRO EQUIPO</h1>
    </div>
    <div class="contenedor-tarjetas">
      <tarjeta-vue
      Nombre="Rodolfo López Olvera"
      Puesto="Secretario Del H. Ayuntamiento"
      Contacto="rodolfo.lopez@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+SECRETARIO+DEL+AYUNTAMIENTO.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+SECRETARIO+DEL+AYUNTAMIENTO.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Tatiana Dessire Oviedo Gómez"
      Puesto="Directora General de Bienestar Integral"
      Contacto="tatiana.dessire@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+DIRECCION+DE+BIENESTAR+INTEGRAL.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+DIRECCION+DE+BIENESTAR+INTEGRAL.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Edith Ma Cristina Vallarta Azuara"
      Puesto="Directora De Area De La Salud"
      Contacto="edith.vallarta@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+DIRECCION+DE+AREA+SALUD.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+DIRECCION+DE+AREA+SALUD.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Idania Karina Lopez Reyes"
      Puesto="Directora de Desarrollo Sostenible"
      Contacto="idania.karina@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+DIRECCION+DESARROLLO+SOSTENIBLE.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+DIRECCION+DESARROLLO+SOSTENIBLE.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Victor Alejandro Vázquez Ramírez"
      Puesto="Director De Área De Desarrollo Urbano"
      Contacto="victor.alejandro@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+DESARROLLO+URBANO.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+DESARROLLO+URBANO.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Artemio Hernández Reséndez"
      Puesto="Director De Área De Movilidad"
      Contacto="@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+DIRECTOR+DE+A%CC%81REA+DE+MOVILIDAD.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+DIRECCION+DE+AREA+DE+MOVILIDAD.pdf"
      />
      <tarjeta-vue
      Nombre="Adrián Mauricio Sánchez Mitre"
      Puesto="Director De Seguridad Pública Y Protección Ciudadana"
      Contacto="@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+COMISARIO.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+COMISARIO.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Victor Hugo Aguilar Pavón"
      Puesto="Director De Innovación Gubernamental"
      Contacto="victor.pavon@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+INOVACION+GUBERNAMENTAL.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+IINOVACION+GUBERNAMENTAL.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Elizabeth Aglaya Soriano López"
      Puesto="Contralora Municipal"
      Contacto="elizabeth.soriano@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+CONTRALORIA+MUNICIPAL.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+CONTRALORIA+MUNICIPAL.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Thamara Ivone González Rodríguez"
      Puesto="Directora De Las Mujeres, Inclusión Y Equidad"
      Contacto="thamara.gonzalez@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+EQUIDAD+E+IGUALDAD+DE+GENERO.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+EQUIDAD+E+IGUALDAD+DE+GENERO.docx.pdf"
      />
      <tarjeta-vue
      Nombre="Jorge Adrián Cruz Flores"
      Puesto="Defensor Municipal De Derechos Humanos"
      Contacto="jorge.adrian@nicolasromero.gob.mx"
      logros="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-logros/LOGROS+DEFENSOR+MUNICIPAL.docx.pdf"
      cv="https://nicolas-romero.s3.us-west-1.amazonaws.com/organigrama/pdf-cv/CV+DEFENSOR+MUNICIPAL.docx.pdf"
      />
    </div>
  </main>
</template>

<script>
import TarjetaVue from '../components/TarjetaPerfil.vue'
import HeaderPrincipal from '../components/HeaderPrincipal.vue'

export default {
  components: {
    TarjetaVue,
    HeaderPrincipal,
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway&family=Roboto:ital@0;1&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&family=Raleway&family=Roboto:ital,wght@0,400;1,100;1,400&display=swap');

body {
  margin: 0;
}
.contenedor-tarjetas {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.titulo {
  text-align: left;
  margin-bottom: 80px;
  margin-left: 20px;
  border-bottom: 3px solid #54191b;
  margin-right: 20px;
  color: hsl(213.3, 7.1%, 24.9%);
}
h1 {
  font-family: roboto;
}
@media (min-width: 1024px) {
  .titulo {
  margin-left: 50px;
  border-bottom: 3px solid #54191b;
  margin-right: 50px;
  color: hsl(213.3, 7.1%, 24.9%);
}
}
</style>
