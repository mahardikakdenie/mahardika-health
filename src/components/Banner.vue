<template>
  <!-- <carousel
    class="hero-items"
    :dots="false"
    :items="1"
    :nav="false"
    :autoplay="true"
  > -->
  <div class="container flex flex-wrap mt-4">
    <div class="grid grid-rows-1">
      <div class="grid grid-cols-2">
        <div class="container">
          <p class="text-6xl font-bold text-left dark:text-white">
            We Care About <br />
            Your Health
          </p>
          <p class="text-lg text-[#232C19] text-left dark:text-white">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
            modi aperiam optio enim dignissimos dolores sunt consequuntur
            aliquam quas incidunt exercitationem eveniet eaque placeat repellat,
            saepe quod ipsum consequatur minus repudiandae inventore culpa
            perspiciatis mollitia! Fugit voluptates dolore incidunt molestias?
          </p>
        </div>
        <!-- <div class="flex items-center">
        </div> -->
        <div class="flex items-center">
          <img
            src="https://img.freepik.com/free-vector/flat-hand-drawn-patient-taking-medical-examination_52683-57829.jpg?size=626&ext=jpg&ga=GA1.1.2125335580.1636954285"
            alt=""
            class="rounded-lg bg-transparent"
          />
        </div>
      </div>
    </div>
    <div class="grid grid-cols-2">
      <input
        type="email"
        id="email"
        class="
          bg-gray-50
          border border-gray-300
          text-gray-900 text-sm
          rounded-lg
          focus:ring-blue-500 focus:border-blue-500
          block
          w-full
          py-2.5
          px-12
          dark:bg-gray-700
          dark:border-gray-600
          dark:placeholder-gray-400
          dark:text-white
          dark:focus:ring-blue-500
          dark:focus:border-blue-500
        "
        placeholder="name@flowbite.com"
        required
      />

      <button
        type="button"
        class="
          ml-3
          text-gray-900
          bg-gradient-to-r
          from-red-200
          via-red-300
          to-yellow-200
          hover:bg-gradient-to-bl
          focus:ring-4 focus:outline-none focus:ring-red-100
          dark:focus:ring-red-400
          font-medium
          rounded-lg
          text-sm
          px-10
          
          py-3
          text-center
          font-bold
          text-white
        "
      >
        Login
      </button>
    </div>
  </div>
  <!-- </carousel> -->
</template>

<script >
import carousel from "vue-owl-carousel";
export default {
  components: {
    carousel,
  },
};
</script>

<style>
</style>