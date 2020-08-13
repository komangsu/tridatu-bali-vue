<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white pt-3 fixed-top navbar-border-bottom">
      <div class="container">
        <a class="navbar-brand font-italic" href="#">
          <img src="@/assets/tridatu.png" width="auto" height="42" alt=" "/>
          <span class="text-dark font-weight-bold align-self-center align-text-top">
            Tridatu<span class="text-muted font-weight-bold"> Bali ID</span>
          </span>
        </a>
        <div class="navbar-bell-toggler d-lg-none">
          <a href="#" class="notification">
            <i class="far fa-bell fa-lg"></i>
            <span class="badge badge-danger">4</span>
          </a>
        </div>
        <div class="navbar-cart-toggler d-lg-none">
          <a href="#" class="notification">
            <i class="far fa-shopping-cart fa-lg"></i>
            <span class="badge badge-danger">4</span>
          </a>
        </div>
        <button
          class="navbar-toggler border-0"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav">
            <li class="nav-item dropdown mr-2">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                Kategori
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Aksesoris</a>
                <a class="dropdown-item" href="#">Baju</a>
                <a class="dropdown-item" href="#">Celana</a>
                <a class="dropdown-item" href="#">Jaket</a>
                <a class="dropdown-item" href="#">Tas Selempang</a>
              </div>
            </li>
            <li class="nav-item active mr-2">
              <a class="nav-link" href="#"
                >Promo <span class="sr-only">(current)</span></a
              >
            </li>
          </ul>
          <form class="form-inline mr-4">
            <div class="input-group w-29 w-500 w-100-s">
              <input
                class="form-control border-0 bg-gray-search outline-search"
                type="search"
                placeholder="Search"
                aria-label="Search"
              />
              <div class="input-group-append">
                <button class="btn bg-gray-search outline-search" type="button">
                  <i class="far fa-search"></i>
                </button>
              </div>
            </div>
          </form>
          <ul class="navbar-nav">
            <div class="navbar-bell-toggler align-self-center d-none d-lg-block">
              <a href="#" class="notification">
                <i class="far fa-bell fa-lg"></i>
                <span class="badge badge-danger">4</span>
              </a>
            </div>
            <div class="navbar-cart-toggler align-self-center mr-2 d-none d-lg-block">
              <a href="#" class="notification">
                <i class="far fa-shopping-cart fa-lg"></i>
                <span class="badge badge-danger">4</span>
              </a>
            </div>

            <div class="border-right mr-4"></div>

            <li class="nav-item d-lg-none">
              <a class="nav-link" href="#">Masuk</a>
            </li>
            <li class="nav-item d-lg-none">
              <a class="nav-link" href="#">Daftar</a>
            </li>

            <li class="nav-item mr-2 align-self-center d-none d-lg-block">
              <a type="button" class="btn btn-sm btn-outline-dark">Masuk</a>
            </li>
            <li class="nav-item align-self-center d-none d-lg-block">
              <a type="button" class="btn btn-sm btn-secondary">Daftar</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Navbar -->
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.w-500 {
  width: 480px;
}
@media (max-width: 1199.98px) {
  .w-29 {
    width: 29vw !important;
  }
}
.bg-gray-search {
  background-color: #f1f3f5;
}
.outline-search {
  box-shadow: 0 0 0 0 transparent !important;
  text-decoration: none !important;
}
/* Define what each icon button should look like */
.button-badge {
  color: white;
  display: inline-block; /* Inline elements with width and height. TL;DR they make the icon buttons stack from left-to-right instead of top-to-bottom */
  position: relative; /* All 'absolute'ly positioned elements are relative to this one */
}

.badge-notif {
  background-color: #fa3e3e;
  border-radius: 2px;
  color: white;

  padding: 2px 3px;
  font-size: 10px;

  position: absolute; /* Position the badge within the relatively positioned button */
  top: 5px;
  right: 0;
}
.pill {
  padding-right: 0.6em;
  padding-left: 0.6em;
  border-radius: 10rem;
}
.navbar-border-bottom {
  box-shadow: rgba(0, 0, 0, 0.18) 0px 1px 15px !important;
}
/* Medium devices (tablets, less than 992px) */
@media (max-width: 991.98px) {
  .w-100-s {
    width: 100%!important;
  }
}
.navbar-bell-toggler {
    padding: .25rem .75rem;
    font-size: 1rem;
    line-height: 1;
    background-color: transparent;
    border: 1px solid transparent;
    border-radius: .25rem;
    margin-left: auto;
}
.navbar-cart-toggler {
    padding: .25rem .75rem;
    font-size: 1rem;
    line-height: 1;
    background-color: transparent;
    border: 1px solid transparent;
    border-radius: .25rem;
}
.navbar-bell-toggler .badge {
  background: #e85044;
  position: absolute;
  top: -6px;
  right: -5px;
  font-size: 10px;
  border-radius: 50%;
}
.navbar-cart-toggler .badge {
  background: #e85044;
  position: absolute;
  top: -6px;
  right: -5px;
  font-size: 10px;
  border-radius: 50%;
}
.notification {
  color: rgba(0,0,0,.5);
  position: relative;
}
</style>
