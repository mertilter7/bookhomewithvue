<template>
    <nav class="navbar navbar-expand-lg bgnavbar">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
        <img class="img-fluid logo" src="../assets/logo.png" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item me-5">
          <a class="nav-link active" aria-current="page" href="#">Anasayfa</a>
        </li>
        <li class="nav-item me-5">
          <a class="nav-link" href="#">Kitaplar</a>
        </li>
        <li class="nav-item me-5">
          <a class="nav-link" href="#">Hakkimizda</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>
<script>
export default {
    name: 'navbar'
}
</script>

<style scoped>

.bgnavbar{
    background-color: plum;
    
}
.logo{
    width: 50px;
}

.nav-link{
    color: white;
    font-weight: bold;
}
</style>
