<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
          <a class="navbar-item" href="#">
            <img src="../../assets/images/icon.png" alt="BomberStore" width="40" height="40">
          </a>
      </div>
      <div class="navbar-menu" id="navMenu">
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link" href="/documentation/overview/start/">
              Docs
            </a>
            <div class="navbar-dropdown is-boxed">
              <a class="navbar-item" href="/documentation/overview/start/">
                Overview
              </a>
              <a class="navbar-item" href="https://bulma.io/documentation/modifiers/syntax/">
                Modifiers
              </a>
              <a class="navbar-item" href="https://bulma.io/documentation/columns/basics/">
                Columns
              </a>
              <a class="navbar-item" href="https://bulma.io/documentation/layout/container/">
                Layout
              </a>
              <a class="navbar-item" href="https://bulma.io/documentation/form/general/">
                Form
              </a>
              <hr class="navbar-divider">
              <a class="navbar-item" href="https://bulma.io/documentation/elements/box/">
                Elements
              </a>
              <a class="navbar-item is-active" href="https://bulma.io/documentation/components/breadcrumb/">
                Components
              </a>
            </div>
          </div>

          <div class="navbar">
              <a class="navbar-item">Clientes</a>
          </div>
          <div class="navbar">
              <a class="navbar-item">Inventario</a>
          </div>
          <div class="navbar">
              <a class="navbar-item">Ventas</a>
          </div>
          <div class="navbar">
              <a class="navbar-item">Administración</a>
          </div>
      </div>
    </nav>  
  </div>
</template>