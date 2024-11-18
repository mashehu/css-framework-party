<script>
  export let count;
</script>

<div class="space-y-6">
  <!-- Button Demo -->
  <section>
    <h4 class="text-sm font-semibold mb-2">Buttons</h4>
    <div class="space-y-2">
      <button class="w-full bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-6 rounded-full transition-colors" on:click={() => $count += 1}>
        Primary ({$count})
      </button>
      <button class="w-full bg-gray-500 hover:bg-gray-700 text-white font-bold py-2 px-6 rounded-full transition-colors">
        Secondary
      </button>
      <button class="w-full bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-6 rounded-full transition-colors">
        Danger
      </button>
    </div>
  </section>

  <!-- Alert Demo -->
  <section>
    <h4 class="text-sm font-semibold mb-2">Alerts</h4>
    <div class="space-y-2">
      <div class="bg-blue-100 border-l-4 border-blue-500 text-blue-700 p-4">
        Info alert - Check this out!
      </div>
      <div class="bg-red-100 border-l-4 border-red-500 text-red-700 p-4">
        Danger alert - Something went wrong!
      </div>
    </div>
  </section>

  <!-- Card Demo -->
  <section>
    <h4 class="text-sm font-semibold mb-2">Card</h4>
    <div class="bg-white shadow-lg rounded-lg overflow-hidden">
      <img src="https://picsum.photos/400/200" alt="Sample" class="w-full h-48 object-cover"/>
      <div class="p-6">
        <h5 class="text-lg font-bold mb-2">Sample Card</h5>
        <p class="text-gray-600 mb-4">This is an example card component styled with Tailwind CSS</p>
        <div class="flex gap-2">
          <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2.5 py-0.5 rounded">Tag 1</span>
          <span class="bg-green-100 text-green-800 text-xs font-semibold px-2.5 py-0.5 rounded">Tag 2</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Form Demo -->
  <section>
    <h4 class="text-sm font-semibold mb-2">Form Elements</h4>
    <div class="space-y-4">
      <div>
        <label class="block text-sm font-medium text-gray-700 mb-1">Input Field</label>
        <input type="text" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="Enter text..."/>
      </div>
      <div>
        <label class="block text-sm font-medium text-gray-700 mb-1">Select Menu</label>
        <select class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
          <option>Option 1</option>
          <option>Option 2</option>
          <option>Option 3</option>
        </select>
      </div>
    </div>
  </section>

  <!-- Navigation -->
  <section>
    <h4 class="text-sm font-semibold mb-2">Navigation</h4>
    <nav class="bg-gray-800 rounded-lg">
      <div class="px-4 py-3">
        <div class="flex items-center justify-between">
          <div class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
            </svg>
          </div>
          <div class="flex space-x-4">
            <a href="#" class="text-gray-300 hover:text-white px-2 py-1">Home</a>
            <a href="#" class="text-gray-300 hover:text-white px-2 py-1">About</a>
            <a href="#" class="text-gray-300 hover:text-white px-2 py-1">Contact</a>
          </div>
        </div>
      </div>
    </nav>
  </section>
</div>