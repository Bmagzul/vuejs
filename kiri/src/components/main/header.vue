<template>
	<nav class="navbar navbar-expand navbar-expand-sm navbar-dark bg-dark fixed-top">
      <a class="navbar-brand mr-1"
          href="javascript:;"
          onclick="window.location.reload()">

          <span class="codeCol">
              Col
          </span>
          <span class="nameCol">
              Colegio
          </span>
      </a>

      <button class="btn btn-sm text-white order-1 order-sm-0" id="menuKpp" href="javascript:;">
          <i class="fas fa-bars"></i>
      </button>
          

      <ul class="navbar-nav ml-auto">
          <li class="nav-item dropdown mx-1">
              <a class="nav-link" href="#" id="alertsDropdown">
                  <i class="fas fa-bell"></i>
                  <span class="badge badge-danger">9+</span>
              </a>
          </li>
          <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" 
                  href="javascript:;" 
                  id="userDropdown" 
                  role="button" 
                  data-toggle="dropdown" 
                  aria-haspopup="true" 
                  aria-expanded="false">
                  <i class="fas fa-user"></i>
              </a>

              <div class="dropdown-menu dropdown-menu-right" aria-labelledby="userDropdown">
                  <a class="dropdown-item py-1" href="javascript:;">
                      <i class="fa fa-user-cog fa-fw"></i> Cuenta
                  </a>
                  <a class="dropdown-item py-1" href="javascript:;">
                      <i class="fa fa-unlock-alt fa-fw"></i> Cambiar contraseña
                  </a>
                  <div class="dropdown-divider"></div>
                  <a class="dropdown-item py-1"> <i class="fa fa-sign-out-alt fa-fw"></i> Cerrar Sesion
                  </a>
              </div>
          </li>
      </ul>
  </nav>
</template>

<script>
	export default {
		name: "Hheader"
	}
</script>