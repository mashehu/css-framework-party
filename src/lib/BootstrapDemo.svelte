<script>
  import 'bootstrap/dist/css/bootstrap.min.css';
</script>

<div class="bootstrap-container">
  <div class="bootstrap-content">
    <!-- Button Demo -->
    <section>
      <h4 class="h6">Buttons</h4>
      <div class="d-grid gap-2">
        <button class="btn btn-primary">Primary</button>
        <button class="btn btn-secondary">Secondary</button>
        <button class="btn btn-danger">Danger</button>
        <button class="btn btn-outline-primary">Primary Outlined</button>
        <button class="btn btn-outline-secondary">Secondary Outlined</button>
        <button class="btn btn-outline-danger">Danger Outlined</button>
      </div>
    </section>
<!-- Button Group Demo -->
    <section>
      <h4 class="h6">Button Group</h4>
      <!-- Solid Variant -->
      <div class="btn-group mb-3" role="group" aria-label="Basic example">
        <button type="button" class="btn btn-primary">Left</button>
        <button type="button" class="btn btn-primary">Middle</button>
        <button type="button" class="btn btn-primary">Right</button>
      </div>
    </section>
    <!-- Alert Demo -->
    <section>
      <h4 class="h6">Alerts</h4>
      <div class="alert alert-primary" role="alert">
        Info alert - Check this out!
      </div>
      <div class="alert alert-danger" role="alert">
        Danger alert - Something went wrong!
      </div>
    </section>

    <!-- Card Demo -->
    <section>
      <h4 class="h6">Card</h4>
      <div class="bootstrap-card card">
        <img src="https://picsum.photos/400/200" class="card-img-top" alt="Sample"/>
        <div class="bootstrap-card-body card-body">
          <h5 class="bootstrap-card-title card-title">Sample Card</h5>
          <p class="bootstrap-card-text card-text">This is an example card component styled with Bootstrap</p>
          <div class="mt-2">
            <span class="badge bg-primary me-1">Tag 1</span>
            <span class="badge bg-success">Tag 2</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Form Demo -->
    <section>
      <h4 class="h6">Form Elements</h4>
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
      <h4 class="h6">Navigation</h4>
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
</div>

<style>
  :global(.bootstrap-container) {
    isolation: isolate;
  }
  
  :global(.bootstrap-container) {
    font-family: var(--bs-body-font-family);
    --bs-heading-color: #212529
  }

  /* Override Bulma card styles completely */
  :global(.bootstrap-container .bootstrap-card.card) {
    --bulma-card-color: none !important;
    --bulma-card-background-color: none !important;
    --bulma-card-shadow: none !important;
    --bulma-card-radius: none !important;
    background-color: #fff !important;
    border-radius: 0.375rem !important;
    box-shadow: none !important;
    color: var(--bs-body-color) !important;
    border: 1px solid rgba(0,0,0,.125) !important;
    position: relative !important;
    display: flex !important;
    flex-direction: column !important;
    min-width: 0 !important;
    word-wrap: break-word !important;
    background-clip: border-box !important;
    padding: 0 !important;
  }

  :global(.bootstrap-container .card-body) {
    padding: 1rem !important;
    color: var(--bs-card-color) !important;
  }

  :global(.bootstrap-container .card-title) {
    margin-bottom: 0.5rem !important;
    color: var(--bs-card-title-color) !important;
    font-weight: 500 !important;
  }

  :global(.bootstrap-container .card-text) {
    color: var(--bs-card-color) !important;
  }
  section {
    margin-bottom: 1rem !important;
  }
</style>
