<script>
    export let pageCurrent;
</script>
<nav class="navbar navbar-expand-xl navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="/">Mood Tracker by Evan</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarBasic" aria-controls="navbarBasic" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse show" id="navbarBasic">
        <ul class="navbar-nav me-auto mb-2 mb-xl-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/">Home</a>
          </li>
          
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" placeholder="Search" aria-label="Search" value="Page: {pageCurrent}">
          <button class="btn btn-outline-success" type="button">Search</button>
        </form>
      </div>
    </div>
  </nav>