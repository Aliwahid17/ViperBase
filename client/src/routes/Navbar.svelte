<script lang="ts">
</script>

<nav class="bg-white shadow-md z-10  border-gray-200 px-2 sm:px-4 py-2.5  ">
  <div class="container flex flex-wrap items-center justify-between mx-auto">
    <a href="/" class="flex items-center  ">
      <img
        src="logo.svg"
        class="h-6 mr-3 sm:h-9"
        alt="DjangoBase Logo"
        loading="lazy"
      />
      <span class="self-center text-xl font-mono whitespace-nowrap "
        >ViperBase</span
      >
    </a>

    <div class="flex md:order-2 font-semibold ">
      <a
        href="https://www.github.com/"
        class="md:flex hidden items-center mx-2"
        title="GitHub"
        target="_blank"
        rel="noreferrer"
      >
        <img
          src="github.svg"
          class="h-6 sm:h-9"
          alt="GitHub"
          loading="lazy"
        /></a
      >
      <a href="/signin">
        <button
          type="button"
          class="text-white md:flex hidden hover:text-white  bg-gradient-to-r from-red-500 to-red-800 hover:from-green-400 hover:to-lime-500 mx-2 hover:bg-green-600 focus:ring-4 focus:outline-none focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0  "
          >Get Started</button
        >
      </a>

      <button
        data-collapse-toggle="navbar-cta"
        type="button"
        class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200   "
        aria-controls="navbar-cta"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-6 h-6"
          aria-hidden="true"
          fill="currentColor"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
            clip-rule="evenodd"
          />
        </svg>
      </button>
    </div>
    <div
      class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
      id="navbar-cta"
    >
      <ul
        class="flex flex-col p-4 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-white   "
      >
        <!-- <li>
          <a href="/"
            class="block py-2 pl-3 pr-4 text-white bg-green-700 rounded md:bg-transparent md:text-green-700 md:p-0 "
            aria-current="page">Home</a>
        </li> -->
        <li>
          <a
            href="/"
            class="block   font-semibold py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-green-700 md:p-0      "
            >Docs</a
          >
        </li>
        <li>
          <a
            href="https://www.github.com"
            target="_blank"
            rel="noreferrer"
            class="block py-2 pl-3 pr-4 text-gray-700  font-semibold rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-green-700 md:p-0      "
            >Discussions</a
          >
        </li>
        <li>
          <a
            href="/"
            class="block py-2 pl-3 pr-4 text-gray-700 font-semibold  rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-green-700 md:p-0      "
            >Support Us</a
          >
        </li>
      </ul>
    </div>
  </div>
</nav>
