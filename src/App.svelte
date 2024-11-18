<script>
  import { writable } from 'svelte/store';
  import TailwindDemo from './lib/TailwindDemo.svelte';
  import BootstrapDemo from './lib/BootstrapDemo.svelte';
  import BulmaDemo from './lib/BulmaDemo.svelte';

  const count = writable(0);
  
  const frameworks = {
    tailwind: {
      name: 'Tailwind CSS',
      component: TailwindDemo
    },
    bootstrap: {
      name: 'Bootstrap',
      component: BootstrapDemo
    },
    bulma: {
      name: 'Bulma',
      component: BulmaDemo
    }
  };
</script>

<div class="container mx-auto p-4 max-w-[1400px]">
  <h2 class="text-2xl font-bold mb-6 text-center">CSS Framework Comparison</h2>
  
  <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
    {#each Object.entries(frameworks) as [key, framework]}
      <div class="p-6 bg-gray-50 rounded-lg">
        <h3 class="text-xl font-bold mb-6 text-center">{framework.name}</h3>
        <svelte:component this={framework.component} {count} />
      </div>
    {/each}
  </div>
</div>

<style>
  :global(body) {
    margin: 0;
    font-family: system-ui, sans-serif;
    background-color: white;
  }
</style>