componente coincidente para la ruta proporcionada.
<template>
  <div>
    <!-- Nav bar -->
    <nav
      class="navbar navbar-dark bg-primary justify-content-between flex-nowrap flex-row"
      style="background: green !important;"
    >
      <div class="container">
        <a class="navbar-brand float-left">CALCULADORA DE HUELLA DE CARBONO</a>
        <ul class="nav navbar-nav flex-row float-right" style="grid-gap: 1em;">

          <li class="nav-item ml-3">
            <router-link class="nav-link" to="/home">Inicio</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link pr-1" to="/menu">Menú</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link pr-2" to="/tips">Tips</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link pr-3" to="/cálculo">Calcular Huella CO2</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link pr-4" to="/administrador">Administrador</router-link>
          </li>
          
        </ul>
      </div>
    </nav>
    <!-- Router view -->
    <!-- <img src="../src/assets/img/bosque1.jpg" alt="" /> -->
    <div class="container mt-5">
      <router-view></router-view>
    </div>
  </div>
</template>
