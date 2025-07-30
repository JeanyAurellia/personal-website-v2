<template>
  <section class="flex flex-col justify-center bg-[#141720] text-white px-50 py-20 h-screen">
    <div class="grid md:grid-cols-2 gap-20 items-start">
      <!-- Kiri: Teks dan info -->
      <div class="flex flex-col space-y-9 gap-7">
        <h1 class="text-5xl font-bold">
          Contact <span class="text-yellow-400">Me</span>
        </h1>
        <p class="text-sm text-gray-400 max-w-md">
          There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.
        </p>

        <div class="mt-6">
          <h3 class="font-semibold text-lg">Email</h3>
          <p class="text-sm text-gray-300 mt-1">abcd@gmail.com</p>
        </div>
      </div>

      <!-- Kanan: Form -->
    <div class="flex flex-col space-y-4 gap-7">
    <input
        type="text"
        placeholder="Name"
        class="w-86 bg-[#1F2937] text-white p-3 rounded-md outline-none"
    />
    <input
        type="email"
        placeholder="Email"
        class="w-86 bg-gray-800 text-white p-3 rounded-md outline-none"
    />
    <textarea
        rows="5"
        placeholder="Message"
        class="w-full bg-gray-800 text-white p-3 rounded-md outline-none resize-none"
    ></textarea>
    <button
        class="self-center bg-yellow-400 text-black px-6 py-2 rounded-md hover:bg-yellow-500 transition"
    >
        Contact us
    </button>
    </div>

    </div>
  </section>
</template>
