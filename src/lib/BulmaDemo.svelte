<script>
  import 'bulma/css/bulma.min.css';
  import '@fortawesome/fontawesome-free/css/all.min.css';
</script>

<div class="bulma-container" data-theme="light">
  <div class="content">
    <!-- Button Demo -->
    <section class="mb-4">
      <h4 class="is-size-6 mb-2">Buttons</h4>
      <div class="buttons">
        <button class="button is-primary">Primary
        </button>
        <button class="button is-light">
          Secondary
        </button>
        <button class="button is-danger is-fullwidth">
          Danger
        </button>
        <button class="button is-primary is-outlined">
          Primary Outlined
        </button>
        <button class="button is-light is-outlined">
          Secondary Outlined
        </button>
        <button class="button is-danger is-outlined is-fullwidth">
          Danger Outlined
        </button>
      </div>
    </section>
    <!-- Button Group Demo -->
    <section class="mb-4">
      <h4 class="is-size-6 mb-2">Button Group</h4>
      <!-- Solid Variant -->
      <div class="buttons has-addons mb-3">
        <button class="button is-primary">Left</button>
        <button class="button is-primary">Middle</button>
        <button class="button is-primary">Right</button>
      </div>
    </section>

    <!-- Alert Demo -->
    <section class="mb-4">
      <h4 class="is-size-6 mb-2">Alerts</h4>
      <div class="notification is-info">
        Info alert - Check this out!
      </div>
      <div class="notification is-danger">
        Danger alert - Something went wrong!
      </div>
    </section>

    <!-- Card Demo -->
    <section class="mb-4">
      <h4 class="is-size-6 mb-2">Card</h4>
      <div class="card">
        <div class="card-image">
          <figure class="image">
            <img src="https://picsum.photos/400/200" alt="Sample"/>
          </figure>
        </div>
        <div class="card-content">
          <div class="media">
            <div class="media-content">
              <p class="title is-4">Sample Card</p>
            </div>
          </div>

          <div class="content">
            <p>This is an example card component styled with Bulma</p>
            <div class="tags">
              <span class="tag is-info">Tag 1</span>
              <span class="tag is-success">Tag 2</span>
            </div>
          </div>
        </div>
        <footer class="card-footer">
          <a href="#" class="card-footer-item">Action 1</a>
          <a href="#" class="card-footer-item">Action 2</a>
        </footer>
      </div>
    </section>

    <!-- Form Demo -->
    <section class="mb-4">
      <h4 class="is-size-6 mb-2">Form Elements</h4>
      <div class="field">
        <label class="label">Input Field</label>
        <div class="control">
          <input class="input has-background-white has-text-dark" type="text" placeholder="Enter text..."/>
        </div>
      </div>
      <div class="field">
        <label class="label has-text-dark">Select Menu</label>
        <div class="control">
          <div class="select is-fullwidth">
            <select class="has-background-white has-text-dark">
              <option>Option 1</option>
              <option>Option 2</option>
              <option>Option 3</option>
            </select>
          </div>
        </div>
      </div>
    </section>

    <!-- Navigation -->
    <section class="mb-4">
      <h4 class="is-size-6 mb-2">Navigation</h4>
      <nav class="navbar is-dark is-spaced">
        <div class="navbar-brand">
          <a class="navbar-item" href="#">
            <span class="icon">
              <i class="fas fa-home"></i>
            </span>
          </a>
        </div>
        <div class="navbar-menu is-active">
          <div class="navbar-start">
            <a class="navbar-item" href="#">Home</a>
            <a class="navbar-item" href="#">About</a>
            <a class="navbar-item" href="#">Contact</a>
          </div>
        </div>
      </nav>
    </section>

    
  </div>
</div>

<style>
  :global(.bulma-container) {
    isolation: isolate;
  }
  
  :global(.bulma-container) :global(.content) {
    font-family: BlinkMacSystemFont, -apple-system, "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  }
</style>