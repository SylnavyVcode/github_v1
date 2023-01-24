<template>
  <div>
    <nav class="navbar navbar-lg bgBody">
      <div class="container-fluid">
        <div class="row vw-100">
          <div class="col-1 m-0">
            <button
              class="navbar-toggler px-2"
              type="button"
              data-bs-toggle="offcanvas"
              data-bs-target="#offcanvasExample"
              aria-controls="navbarTogglerDemo01"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>

            <div
              class="offcanvas offcanvas-start bg-info"
              tabindex="-1"
              id="offcanvasExample"
              aria-labelledby="offcanvasExampleLabel"
            >
              <div class="offcanvas-header">
                <h5 class="offcanvas-title" id="offcanvasExampleLabel">
                  Sylnavy Mabika
                </h5>
                <button
                  type="button"
                  class="btn-close"
                  data-bs-dismiss="offcanvas"
                  aria-label="Close"
                ></button>
              </div>
              <div class="offcanvas-body">
                <div class="dropdown mt-3">
                  <button
                    class="btn btn-secondary dropdown-toggle"
                    type="button"
                    data-bs-toggle="dropdown"
                  >
                    Dropdown button
                  </button>
                  <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li>
                      <a class="dropdown-item" href="#">Another action</a>
                    </li>
                    <li>
                      <a class="dropdown-item" href="#">Something else here</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div
            class="col d-flex justify-content-between text-align-center align-items-center"
          >
            <a
              class="navbar-brand text-warning fw-bold bg-dark rounded px-2"
              href="#"
              >SV_WebDev</a
            >

            <form class="" role="search">
              <div class="input-group">
                <input
                  type="text"
                  class="form-control bg-outline-success"
                  placeholder="Search"
                  aria-label="Recipient's username"
                  aria-describedby="button-addon2"
                />
                <button
                  class="btn btn-outline-warning"
                  type="button"
                  id="button-addon2"
                >
                  Search
                </button>
              </div>
            </form>

            <div class=" col-3 p-0 mb-lg-0 d-flex justify-content-end align-items-center text-align-center">
              <a class="text-warning" aria-current="page" href="#"
                ><i class="bi bi-github"></i
              ></a>
              <a class="mx-2 text-warning" href="#"
                ><i class="bi bi-linkedin"></i
              ></a>
              <a class="me-2 text-warning"><i class="bi bi-twitter"></i></a>
              <a class="text-warning"><i class="bi bi-instagram"></i></a>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {};
</script>
<style>
.bgBody {
  background-color: #169cf5;
}
</style>
