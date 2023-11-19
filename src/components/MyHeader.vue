<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Kesumadadi</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-md-end" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link" href="#">Search Data</a>
          <a class="nav-link" href="#">Input Data</a>
          <div class="d-grid gap-2 d-md-flex">
            <button class="btn btn-primary me-md-2" type="button">Button</button>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "MyHeader",
};
</script>

<style scoped>
* {
  margin: 0;
}
.navbar {
  background-color: #d9d9d9;
}

.navbar-brand {
  color: #17191c;
  font-weight: 700;
}
</style>
