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
        <button
          class="navbar-toggler"
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
                <a class="dropdown-item" href="#">T-shirt</a>
                <a class="dropdown-item" href="#">Accessories</a>
                <a class="dropdown-item" href="#">Jacket</a>
              </div>
            </li>
            <li class="nav-item active mr-2">
              <a class="nav-link" href="#"
                >Promo <span class="sr-only">(current)</span></a
              >
            </li>
          </ul>
          <form class="form-inline mr-4">
            <div class="input-group w-500">
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
            <li class="nav-item mr-2">
              <a class="nav-link button-badge" href="#"
                ><i class="far fa-shopping-cart fa-lg"></i>
                <span class="badge-notif pill h6">4</span>
              </a>
            </li>
            <li class="nav-item mr-2">
              <a class="nav-link button-badge" href="#">
                <i class="far fa-bell fa-lg"></i>
                <span class="badge-notif pill h6">4</span>
              </a>
            </li>
            <li class="nav-item mr-2">
              <a class="nav-link" href="#">
                <i class="far fa-heart fa-lg"></i>
              </a>
            </li>

            <div class="border-right mr-4"></div>

            <li class="nav-item mr-2 align-self-center">
              <a type="button" class="btn btn-sm btn-outline-dark">Masuk</a>
            </li>
            <li class="nav-item align-self-center">
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
  width: 30vw !important;
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
</style>
