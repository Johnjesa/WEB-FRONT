<template>
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">ISSFAA</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <router-link class="nav-link active" to="/clientes">Clientes</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/proveedores">Proveedores</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/productos">Productos</router-link>
              </li>

              <li class="nav-item">
                <router-link class="nav-link" to="/pedido">Pedido</router-link>
              </li>
              
            </ul>
          </div>
        </div>
      </nav>
</template>