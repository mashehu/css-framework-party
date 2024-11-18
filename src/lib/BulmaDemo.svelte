<script>
  export let count;
</script>

<div class="content">
  <!-- Button Demo -->
  <section class="mb-4">
    <h4 class="is-size-6 mb-2">Buttons</h4>
    <div class="buttons">
      <button class="button is-primary is-fullwidth mb-2" on:click={() => $count += 1}>
        Primary ({$count})
      </button>
      <button class="button is-light is-fullwidth mb-2">Secondary</button>
      <button class="button is-danger is-fullwidth">Danger</button>
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
        <figure class="image is-4by3">
          <img src="https://picsum.photos/400/200" alt="Sample"/>
        </figure>
      </div>
      <div class="card-content">
        <p class="title is-5">Sample Card</p>
        <p class="subtitle is-6">This is an example card component styled with Bulma</p>
        <div class="tags">
          <span class="tag is-info">Tag 1</span>
          <span class="tag is-success">Tag 2</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Form Demo -->
  <section class="mb-4">
    <h4 class="is-size-6 mb-2">Form Elements</h4>
    <div class="field">
      <label class="label">Input Field</label>
      <div class="control">
        <input class="input" type="text" placeholder="Enter text..."/>
      </div>
    </div>
    <div class="field">
      <label class="label">Select Menu</label>
      <div class="control">
        <div class="select is-fullwidth">
          <select>
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