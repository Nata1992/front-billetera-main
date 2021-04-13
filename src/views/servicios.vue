<template>
  <nav class="navbar navbar-expand-sm navbar-light bg-light">
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarTogglerDemo03"
      aria-controls="navbarTogglerDemo03"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
      <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#"
            >Inicio <span class="sr-only">(current)</span></a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Acerca de Nosotros</a>
        </li>
        <li class="nav-item dropdown dmenu">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbardrop"
            data-toggle="dropdown"
          >
            Nuestros Servicios
          </a>
          <div class="dropdown-menu sm-menu">
            <a class="dropdown-item" href="#">servicio1</a>
            <a class="dropdown-item" href="#">servicio2</a>
            <a class="dropdown-item" href="#">servicio3</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contactanos</a>
        </li>
      </ul>
      <div class="social-part">
        <i class="fa fa-facebook" aria-hidden="true"></i>
        <i class="fa fa-twitter" aria-hidden="true"></i>
        <i class="fa fa-instagram" aria-hidden="true"></i>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "servicios",
};
</script>

<style scoped>
.social-part .fa {
  padding-right: 20px;
}
ul li a {
  margin-right: 20px;
}
</style>
