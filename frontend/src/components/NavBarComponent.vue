<template>
  <nav class="navbar navbar-expand-lg navbar-light">

    <div class="container-fluid">

      <a class="navbar-brand mx-4" href="/">
        <img id="Logo" src="../assets/bablo-logo-removebg-preview.png" alt="Bablo Logo" draggable="false" height="60" />
      </a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <i class="fa fa-bars"></i>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto align-items-center">
          <a class="text-dark text-decoration-none mx-3 mt-2" href="/">
            <h5>Home</h5>
          </a>
          <a class="text-dark text-decoration-none mx-3 mt-2" href="#features">
            <h5>Features</h5>
          </a>
          <a class="text-dark text-decoration-none mx-3 mt-2" href="#platforms">
            <h5>Platforms</h5>
          </a>
          <a class="text-dark text-decoration-none mx-3 mt-2" href="#FAQs">
            <h5>FAQs</h5>
          </a>
          <li class="nav-item ms-3">
            <a class="btn btn-success rounded-pill" href="downloads">Download</a>
          </li>
          <li class="nav-item ms-3">
            <a class="btn btn-dark rounded-pill" data-bs-toggle="modal" data-bs-target="#loginModal">Log In</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>

export default {
  name: "NavBarComponent",
}
</script>

<style scoped>
.navbar-light .navbar-nav .nav-link {
  color: #000;
}

.navbar {
  background-color: gainsboro;
}
</style>