<template>
  <section class="w-full my-24 mx-auto text-gray-800">
    <h1 class="text-4xl text-center pb-14 font-bold">Contact Me</h1>
    <div
      class="relative overflow-hidden bg-no-repeat bg-cover"
      style="
        background-position: 50%;
        background-image: url('https://www.freecodecamp.org/news/content/images/2022/09/jonatan-pie-3l3RwQdHRHg-unsplash.jpg');
        height: 200px;
      "
    ></div>
    <div class="text-gray-800 px-4 md:px-24">
      <div
        class="block rounded-lg shadow-lg py-10 md:py-12 px-4 md:px-6"
        style="
          margin-top: -100px;
          background: hsla(0, 0%, 100%, 0.8);
          backdrop-filter: blur(30px);
        "
      >
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-x-6 mb-12">
          <div class="mb-12 lg:mb-0 text-center mx-auto">
            <i class="fa-solid fa-earth-americas text-4xl text-blue-600 mb-6 mx-auto"></i>
            <h6 class="font-medium">Afghanistan</h6>
          </div>
          <div class="mb-12 lg:mb-0 text-center mx-auto">
            <i
              class="fa-sharp fa-solid fa-location-dot text-4xl text-blue-600 mb-6 mx-auto"
            ></i>
            <h6 class="font-medium">Kabul, 1005</h6>
          </div>
          <div class="mb-6 md:mb-0 text-center mx-auto">
            <i class="fa-solid fa-phone text-4xl text-blue-600 mb-6 mx-auto"></i>
            <h6 class="font-medium">+ 93700487085</h6>
          </div>
          <div class="text-center mx-auto">
            <i class="fa-solid fa-envelope text-4xl text-blue-600 mb-6 mx-auto"></i>
            <h6 class="font-medium">zikrullah.danish12@gmail.com</h6>
          </div>
        </div>
        <div class="max-w-[700px] mx-auto">
          <form>
            <div class="form-group mb-6">
              <input
                type="text"
                class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                id="exampleInput7"
                placeholder="Name"
              />
            </div>
            <div class="form-group mb-6">
              <input
                type="email"
                class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                id="exampleInput8"
                placeholder="Email address"
              />
            </div>
            <div class="form-group mb-6">
              <textarea
                class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                id="exampleFormControlTextarea13"
                rows="3"
                placeholder="Message"
              ></textarea>
            </div>
            <div class="form-group form-check text-center mb-6">
              <input
                type="checkbox"
                class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain mr-2 cursor-pointer"
                id="exampleCheck87"
                checked
              />
              <label
                class="form-check-label inline-block text-gray-800"
                for="exampleCheck87"
                >Send me a copy of this message</label
              >
            </div>
            <button
              type="submit"
              class="w-full px-6 py-2.5 bg-blue-600 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out"
            >
              Send
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>
