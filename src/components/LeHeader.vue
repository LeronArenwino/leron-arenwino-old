<template>
  <nav
    id="header"
    class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark border-bottom"
  >
    <div class="container">
      <a class="navbar-brand" href="#">
        <img width="50" src="@/assets/logo.png" alt="logo-leron" /> Francisco Dueñas
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbar"
        aria-controls="navbar"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbar">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#about-me">About me</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#knowledge">Knowledge</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- /header -->
</template>
