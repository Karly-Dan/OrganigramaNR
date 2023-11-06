<template>
  <div class="contenedor-tarjeta">
    <div>
      <img src="../assets/imagen.jpg" alt="">
    </div>
    <div class="info">
      <div class="contenedor-info">
        <p><b>Nombre:</b> {{ Nombre }}</p>
        <p><strong>Puesto:</strong> {{ Puesto }}</p>
        <p><strong>Contacto:</strong> {{ Contacto }}</p>
      </div>
      <div class="dropdown">
        <button class="dropbtn">Ver mas</button>
        <div class="dropdown-content">
          <a :href="logros" target="_blank">Logros</a>
          <a :href="cv" target="_blank">CV</a>
        </div>
      </div>
      <div class="botones-movil">
        <a :href="logros" target="_blank" class="boton-cv">Logros</a>
        <p style="width: 2px; background-color: white;"></p>
        <a :href="cv" target="_blank" class="boton-logros">CV</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    Nombre: {
      type: String,
      default: '',
    },
    Puesto: {
      type: String,
      default: '',
    },
    Area: {
      type: String,
      default: '',
    },
    Contacto: {
      type: String,
      default: '',
    },
    logros: {
      type: String,
      default: '',
    },
    cv: {
      type: String,
      default: '',
    }
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Raleway&family=Roboto:ital@0;1&display=swap');

body {
  font-family: roboto;
}
.contenedor-tarjeta {
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
  width: fit-content;
  margin-bottom: 100px;
  width: 335px;
}
p {
  margin: 0;
  font-size: 15px;
  line-height: 25px;
}
img {
  width: 335px;
}
.contenedor-info {
  padding: 5px;
  height: 120px;
}
.dropdown {
  display: none;
}
.botones-movil {
  display: flex;
  justify-content: space-around;
  background-color: #54191b;
}
.boton-cv, .boton-logros {
  text-decoration: none;
  color: white;
  padding: 15px;
}
.boton-logros {
  border-right-color: 2px solid white;
}

@media (min-width: 1024px) {
.contenedor-tarjeta {
  width: 360px;
}
img {
  width: 360px;
}
.dropbtn {
  min-width: 360px;
}
.dropbtn {
  background-color: #54191b;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  text-align: center;
  min-width: 360px;
}
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 360px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  text-align: center;
}

.dropdown-content a {
  color: #54191b;;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}
.botones-movil {
  display: none;
}
.dropdown-content a:hover {background-color: #ddd;}

.dropdown:hover .dropdown-content {display: block;}

.dropdown:hover .dropbtn {background-color: rgb(100, 47, 49);}
}
 </style>