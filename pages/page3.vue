<template>
  <!-- component -->
<section class="bg-white dark:bg-slate-700">
        <div class="container px-6 py-8 mx-auto">
            <div class="sm:flex sm:items-center sm:justify-between">
                <div>
                    <h2 class="text-3xl font-bold text-gray-800 dark:text-gray-100">Simple, transparent pricing</h2>
                    <p class="mt-4 text-gray-500 dark:text-gray-400">One Contracts. No surprise fees.</p>
                </div>

                <div class="overflow-hidden p-0.5 mt-6 border rounded-lg dark:border-gray-700">
                    <div class="sm:-mx-0.5 flex">
                        <button class=" focus:outline-none px-3 w-1/2 sm:w-auto py-1 sm:mx-0.5 text-white bg-emerald-500 rounded-lg">One Time</button>
                        <button class=" focus:outline-none px-3 w-1/2 sm:w-auto py-1 sm:mx-0.5 text-gray-800 dark:text-gray-200 dark:hover:bg-gray-700 bg-transparent rounded-lg hover:bg-gray-200">Continuous</button>
                    </div>
                </div>
            </div>

            <div class="grid gap-6 mt-16 -mx-6 sm:gap-8 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
                <div class="px-6 py-4 transition-colors duration-200 transform rounded-lg hover:bg-gray-200 dark:hover:bg-gray-700">
                    <p class="text-lg font-medium text-gray-800 dark:text-gray-100">Website</p>
                    <h4 class="mt-2 text-4xl font-semibold text-gray-800 dark:text-gray-100">$200 <span class="text-base font-normal text-gray-600 dark:text-gray-400">/ Page</span></h4>
                    <p class="mt-4 text-gray-500 dark:text-gray-300">For personal use, Portfolios, Small Buisnesses </p>

                    <div class="mt-8 space-y-8">
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Perosnalized</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">User traffic reports</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Chat support</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">No Maintinance</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Unlimited users</span>
                        </div>
                    </div>

                    <button class="w-full px-4 py-2 mt-10 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-emerald-500 rounded-md hover:bg-emerald-600 focus:outline-none focus:bg-emerald-600" @click="interested('Website')">
                        Purchase
                    </button>
                </div>

                <div class="px-6 py-4 transition-colors duration-200 transform rounded-lg hover:bg-gray-200 dark:hover:bg-gray-700">
                    <p class="text-lg font-medium text-gray-800 dark:text-gray-100">Database</p>
                    <h4 class="mt-2 text-4xl font-semibold text-gray-800 dark:text-gray-100">$1000 <span class="text-base font-normal text-gray-600 dark:text-gray-400">/ Database</span></h4>
                    <p class="mt-4 text-gray-500 dark:text-gray-300">For small companies seeking simple databases for simple storage of Invintory, Employee Information, Customer Information</p>

                    <div class="mt-8 space-y-8">
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Perosnalized Design</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Muli-user capabilities</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">User Training</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Simple Security</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">1 Tb Storage</span>
                        </div>
                    </div>

                    <button class="w-full px-4 py-2 mt-10 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-emerald-500 rounded-md hover:bg-emerald-600 focus:outline-none focus:bg-emerald-600" @click="interested('Database')">
                        Purchase
                    </button>
                </div>

                <div class="px-6 py-4 transition-colors duration-200 transform bg-gray-700 rounded-lg dark:bg-gray-600">
                    <p class="text-lg font-medium text-gray-100">Miscellaneous Project</p>
                    <h4 class="mt-2 text-4xl font-semibold text-gray-100">$2000 <span class="text-base font-normal text-gray-400">/ Project</span></h4>
                    <p class="mt-4 text-gray-300">From Algorithms, Apps, Software Testing, to Securtiy Testing</p>

                    <div class="mt-8 space-y-8">
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-300">Any language</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-300">Collaboration</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-300">Mobile Apps</span>
                        </div>

                    </div>

                    <button class="w-full px-4 py-2 mt-10 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-emerald-500 rounded-md hover:bg-emerald-600 focus:outline-none focus:bg-emerald-600" @click="interested('Miscellaneous Project')">
                        Purchase
                    </button>
                </div>

                <div class="px-6 py-4 transition-colors duration-200 transform rounded-lg hover:bg-gray-200 dark:hover:bg-gray-700">
                    <p class="text-lg font-medium text-gray-800 dark:text-gray-100">Personalized Video Game</p>
                    <h4 class="mt-2 text-4xl font-semibold text-gray-800 dark:text-gray-100">$5000 <span class="text-base font-normal text-gray-600 dark:text-gray-400">/ Game</span></h4>
                    <p class="mt-4 text-gray-500 dark:text-gray-300">For individuals, people looking for collaborators on games, or just to see something new</p>

                    <div class="mt-8 space-y-8">
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Unity</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Unreal Engine 5</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">First/Third Person</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Multi or Single player</span>
                        </div>

                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-emerald-500" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                            </svg>

                            <span class="mx-4 text-gray-700 dark:text-gray-300">Shooter, Adventure, or Calm style</span>
                        </div>
                    </div>

                    <button class="w-full px-4 py-2 mt-10 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-emerald-500 rounded-md hover:bg-emerald-600 focus:outline-none focus:bg-emerald-600" @click="interested('Personalized Game')">
                        Purchase
                    </button>
                </div>
            </div>
        </div>
    </section>
</template>
<script setup>
useHead ({
    title: 'Tomorrow Coding',
    meta: [
    { name: 'About, projects, and more', content: 'Home of Tomorrow Coding' }
  ],
});

const interested = function (item) {
  alert('Thank you for your interest in a ' + item + '!');
}

</script>