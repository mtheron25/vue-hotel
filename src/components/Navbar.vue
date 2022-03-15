<template>
  <div class="container-fluid">
    <nav class="navbar navbar-expand-lg navbar-light">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
          <a class="nav-link" href="#about">About</a>
          <a class="nav-link" href="#contact">Contact</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container-fluid {
  width: 100%;
  position: fixed;
  background-color: #eadaa2;
  /* background-color: transparent !important; */
  border-color: #e7e7e7;
  padding: 2px;
}

.nav-link {
  font-size: 20px;
  color: white;
}
</style>
