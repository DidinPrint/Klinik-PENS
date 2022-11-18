<template>
    <div class="container">
    <nav class="navbar navbar-expand-lg custom_nav-container ">
      <a class="navbar-brand" href="index.html">
        <span>
          Klinik Pens
        </span>
      </a>

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class=""> </span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="index.html">Beranda <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html"> Tentang</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="departments.html">Layanan</a>
          </li>
          
          <li class="nav-item">
            <a class="nav-link" href="doctors.html">Tenaga Kesehatan</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Hubungi Kami</a>
          </li>
          <form class="form-inline">
            <button class="btn  my-2 my-sm-0 nav_search-btn" type="submit">
              <i class="fa fa-search" aria-hidden="true"></i>
            </button>
          </form>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default{
    name:"Navbar"
};
</script>