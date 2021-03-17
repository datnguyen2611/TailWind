<div class="bg-white dark:bg-black">
    <h1 class="text-gray-900 dark:text-white">Dark mode</h1>
    <p class="text-gray-500 dark:text-gray-300">
      The feature you've all been waiting for.
    </p>
  </div>
  <button class="bg-gray-900 text-white-200">
 hahah
</button>

<div class="bg-white dark:bg-black">
   go dark 
  </div>

  <script>

if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
  document.documentElement.classList.add('dark')
} else {
  document.documentElement.classList.remove('dark')
}

// Whenever the user explicitly chooses light mode
localStorage.theme = 'light'

// Whenever the user explicitly chooses dark mode
localStorage.theme = 'dark'

// Whenever the user explicitly chooses to respect the OS preference
localStorage.removeItem('theme')

  </script>