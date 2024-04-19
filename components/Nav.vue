<template>
    <div class="h-64 dark:text-slate-200">
  <header
    class="container mx-auto flex w-full items-center justify-between py-4 px-6"
  >
    <a href="#">
      <div class="w-full text-center text-lg font-bold sm:w-fit sm:text-left">
        <span class="text-cyan-500">Tailwind</span>
        <span class="dark:text-slate-100">Snippets</span>
      </div>
    </a>
    <nav class="hidden bg-white text-base dark:bg-slate-900 sm:block">
      <ul class="flex items-center space-x-2">
        <li class="group relative">
          <a
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/"
          >
            Home
          </a>
        </li>
        <li class="group relative">
          <a
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="#"
          >
            Services
          </a>
          <ul
            class="invisible absolute z-30 space-y-2 rounded-lg border border-slate-50 bg-white p-4 opacity-0 shadow-xl transition-opacity delay-75 ease-in-out group-hover:visible group-hover:opacity-100 dark:border-slate-800 dark:bg-slate-900"
          >
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/web-development"
              >
                Web development
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/digital-marketing"
              >
                Digital marketing
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/brand-strategy"
              >
                Brand strategy
              </a>
            </li>
          </ul>
        </li>
        <li class="group relative">
          <a
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/about"
          >
            About
          </a>
        </li>
        <li class="group relative">
          <a
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-900 no-underline transition hover:text-slate-900 dark:text-slate-50 dark:hover:text-slate-50"
            href="/contact"
          >
            Contact
          </a>
        </li>
      </ul>
    </nav>
    <button
      class="block text-slate-400 hover:text-slate-900 dark:hover:text-slate-50 sm:hidden"
      title="Open navigation menu"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
      >
        <path
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M4 6h16M4 12h16M4 18h16"
        ></path>
      </svg>
    </button>
    <nav
      class="fixed -right-1/2 top-0 z-20 h-full w-1/2 transform overflow-y-auto bg-white py-4 text-base transition dark:bg-slate-900 sm:hidden"
    >
      <ul class="flex flex-col space-y-2">
        <li class="text-right">
          <button
            class="px-6 py-2 text-slate-400 hover:text-slate-900 dark:hover:text-slate-50"
          >
            <svg
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 24 24"
              width="1.2em"
              height="1.2em"
            >
              <path
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 12h14m-4 4l4-4m-4-4l4 4"
              ></path>
            </svg>
          </button>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/"
          >
            Home
          </a>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="#"
          >
            Services
          </a>
          <ul
            class="h-0 space-y-2 overflow-y-hidden bg-slate-50 px-4 py-0 transition-all delay-75 ease-in-out group-hover:h-full group-hover:py-4 dark:bg-slate-800"
          >
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/web-development"
              >
                Web development
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/digital-marketing"
              >
                Digital marketing
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/brand-strategy"
              >
                Brand strategy
              </a>
            </li>
          </ul>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/about"
          >
            About
          </a>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-900 no-underline transition hover:text-slate-900 dark:text-slate-50 dark:hover:text-slate-50"
            href="/contact"
          >
            Contact
          </a>
        </li>
      </ul>
    </nav>
  </header>
  <p class="container mx-auto px-6 py-8">
    
  </p>
</div>
</template>