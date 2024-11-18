<script>
  export let count;
</script>

<div class="space-y-4">
  <!-- Button Demo -->
  <section>
    <h4 class="h6 mb-2">Buttons</h4>
    <div class="d-grid gap-2">
      <button class="btn btn-primary" on:click={() => $count += 1}>
        Primary ({$count})
      </button>
      <button class="btn btn-secondary">Secondary</button>
      <button class="btn btn-danger">Danger</button>
    </div>
  </section>

  <!-- Alert Demo -->
  <section>
    <h4 class="h6 mb-2">Alerts</h4>
    <div class="alert alert-primary" role="alert">
      Info alert - Check this out!
    </div>
    <div class="alert alert-danger" role="alert">
      Danger alert - Something went wrong!
    </div>
  </section>

  <!-- Card Demo -->
  <section>
    <h4 class="h6 mb-2">Card</h4>
    <div class="card">
      <img src="https://picsum.photos/400/200" class="card-img-top" alt="Sample"/>
      <div class="card-body">
        <h5 class="card-title">Sample Card</h5>
        <p class="card-text">This is an example card component styled with Bootstrap</p>
        <div class="mt-2">
          <span class="badge bg-primary me-1">Tag 1</span>
          <span class="badge bg-success">Tag 2</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Form Demo -->
  <section>
    <h4 class="h6 mb-2">Form Elements</h4>
    <div class="mb-3">
      <label class="form-label">Input Field</label>
      <input type="text" class="form-control" placeholder="Enter text..."/>
    </div>
    <div class="mb-3">
      <label class="form-label">Select Menu</label>
      <select class="form-select">
        <option>Option 1</option>
        <option>Option 2</option>
        <option>Option 3</option>
      </select>
    </div>
  </section>

  <!-- Navigation -->
  <section>
    <h4 class="h6 mb-2">Navigation</h4>
    <nav class="navbar navbar-expand navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand d-flex align-items-center" href="#">
          <i class="bi bi-house-door-fill"></i>
        </a>
        <div class="navbar-nav">
          <a class="nav-link active" href="#">Home</a>
          <a class="nav-link" href="#">About</a>
          <a class="nav-link" href="#">Contact</a>
        </div>
      </div>
    </nav>
  </section>
</div>