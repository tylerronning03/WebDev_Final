<template>
    <!-- component -->
<div class="flex items-center justify-center p-12">
  <div class="mx-auto w-full max-w-[550px]">
    <form action="" method="POST">
      <div class="mb-5">
        <label for="name" class="mb-3 block text-base font-medium text-white">
          Full Name
        </label>
        <input
          type="text"
          name="name"
          id="name"
          placeholder="Full Name"
          class="w-full rounded-md border border-emerald-500 bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-emerald-500 focus:shadow-md"
        />
      </div>
      <div class="mb-5">
        <label
          for="email"
          class="mb-3 block text-base font-medium text-white"
        >
          Email Address
        </label>
        <input
          type="email"
          name="email"
          id="email"
          placeholder="example@domain.com"
          class="w-full rounded-md border border-emerald-500 bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-emerald-500 focus:shadow-md"
        />
      </div>
      <div class="mb-5">
        <label
          for="subject"
          class="mb-3 block text-base font-medium text-white"
        >
          Subject
        </label>
        <input
          type="text"
          name="subject"
          id="subject"
          placeholder="Enter your subject"
          class="w-full rounded-md border border-emerald-500 bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-emerald-500 focus:shadow-md"
        />
      </div>
      <div class="mb-5">
        <label for="message" class="mb-3 block text-base font-medium text-white">
          Message
        </label>
        <textarea
          rows="4"
          name="message"
          id="message"
          placeholder="Type your message"
          class="w-full resize-none rounded-md border border-emerald-500 bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-emerald-500 focus:shadow-md"
        ></textarea>
      </div>
      <div>
        <button
          class="hover:shadow-form rounded-md bg-emerald-500 py-3 px-8 text-base font-semibold text-white outline-none"
        >
          Submit
        </button>
      </div>
    </form>
  </div>
</div>
</template>