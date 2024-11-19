<script>
  import TailwindDemo from './lib/TailwindDemo.svelte';
  import BootstrapDemo from './lib/BootstrapDemo.svelte';
  import BulmaDemo from './lib/BulmaDemo.svelte';
</script>

<div class="comparison-container">
  <h1 class="text-2xl font-bold text-center mb-8 text-gray-800">CSS Framework Comparison</h1>
  
  <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-gray-800">
    <div class="framework-card">
      <h2 class="text-xl font-bold text-center mb-6">
      <img src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg" alt="Tailwind CSS Logo" class="inline-block h-6" />
      </h2>
      <div class="framework-content">
      <TailwindDemo />
      </div>
    </div>

    <div class="framework-card">
      <h2 class="text-xl font-bold text-center mb-6">
      <img src="https://camo.githubusercontent.com/3fd9366fc9c6ab48dc26c1d989cf5ffadc55d5266ed49c67efa5931fd3a83ec9/68747470733a2f2f676574626f6f7473747261702e636f6d2f646f63732f352e332f6173736574732f6272616e642f626f6f7473747261702d6c6f676f2d736861646f772e706e67" alt="Bootstrap Logo" class="inline-block h-10 mr-2" />
      Bootstrap
      </h2>
      <div class="framework-content">
      <BootstrapDemo />
      </div>
    </div>

    <div class="framework-card">
      <h2 class="text-xl font-bold text-center mb-6"> 
        <img src="https://raw.githubusercontent.com/jgthms/bulma/refs/heads/main/docs/assets/brand/Bulma%20Logo.svg" alt="Bulma Logo" class="inline-block h-6 mr-2" />
      </h2>
      <div class="framework-content">
        <BulmaDemo />
      </div>
    </div>
  </div>
</div>

<style>
  .comparison-container {
    padding: 1rem;
  }

  .framework-card {
    border-radius: 0.5rem;
    padding: 1.5rem;
  }

  @media (min-width: 768px) {
    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 2rem;
    }
  }
</style>