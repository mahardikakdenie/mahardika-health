<template>
  <div>
    <nav
      class="
        bg-transparent
        border-gray-200
        px-2
        sm:px-4
        py-4
        rounded
        dark:bg-gray-800
      "
    >
      <div class="container flex flex-wrap justify-between items-center">
        <a href="https://flowbite.com" class="flex items-center mr-12">
          <img
            src="https://img.freepik.com/free-vector/wellness-leaf-logo-template-modern-nature-design-vector_53876-136291.jpg?t=st=1648271938~exp=1648272538~hmac=a6cce01e6215a1174c75502d813ad30d9354f94a11bb404c98635b260add4240&w=826"
            class="mr-3 h-16 sm:h-9"
            alt="Flowbite Logo"
          />
          <span
            class="
              self-center
              text-xl
              font-semibold
              whitespace-nowrap
              dark:text-white
              text-[#AB9082]
              font-bold
              
            "
            >MAHARDIKA</span
          ><span
            class="
              text-[#C3AEA2]
              font-bold
              self-center
              text-xl
              font-semibold
              whitespace-nowrap
              dark:text-white
            "
            >Health
          </span>
        </a>
        <button
          data-collapse-toggle="menu--mobile"
          type="button"
          class="
            inline-flex
            items-center
            p-2
            ml-3
            text-sm text-gray-500
            rounded-lg
            md:hidden
            hover:bg-gray-100
            focus:outline-none focus:ring-2 focus:ring-gray-200
            dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600
          "
          aria-controls="menu--mobile"
          aria-expanded="false"
        >
          <span class="sr-only">Open main menu</span>
          <svg
            class="w-6 h-6"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
              clip-rule="evenodd"
            ></path>
          </svg>
          <svg
            class="hidden w-6 h-6"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
        <div class="hidden w-full md:block md:w-auto" id="menu--mobile">
          <ul
            class="
              flex flex-col
              mt-4
              md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium
              text-3xl
            "
          >
            <li>
              <a
                href="#"
                class="
                  block
                  py-2
                  pr-4
                  pl-3
                  text-white
                  bg-blue-700
                  rounded
                  md:bg-transparent md:text-blue-700 md:p-0
                  dark:text-white
                  font-bold
                  text-lg
                "
                aria-current="page"
                >Home</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  py-2
                  pr-4
                  pl-3
                  text-gray-700
                  border-b border-gray-100
                  hover:bg-gray-50
                  md:hover:bg-transparent
                  md:border-0
                  md:hover:text-blue-700
                  md:p-0
                  dark:text-gray-400
                  md:dark:hover:text-white
                  dark:hover:bg-gray-700 dark:hover:text-white
                  md:dark:hover:bg-transparent
                  dark:border-gray-700
                  font-bold
                  text-lg
                "
                >Best Service</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  py-2
                  pr-4
                  pl-3
                  text-gray-700
                  border-b border-gray-100
                  hover:bg-gray-50
                  md:hover:bg-transparent
                  md:border-0
                  md:hover:text-blue-700
                  md:p-0
                  dark:text-gray-400
                  md:dark:hover:text-white
                  dark:hover:bg-gray-700 dark:hover:text-white
                  md:dark:hover:bg-transparent
                  dark:border-gray-700
                  font-bold
                  text-lg
                "
                >Consulting</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  py-2
                  pr-4
                  pl-3
                  text-gray-700
                  border-b border-gray-100
                  hover:bg-gray-50
                  md:hover:bg-transparent
                  md:border-0
                  md:hover:text-blue-700
                  md:p-0
                  dark:text-gray-400
                  md:dark:hover:text-white
                  dark:hover:bg-gray-700 dark:hover:text-white
                  md:dark:hover:bg-transparent
                  dark:border-gray-700
                  font-bold
                  text-lg
                "
                >Pricing</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  py-2
                  pr-4
                  pl-3
                  text-gray-700
                  hover:bg-gray-50
                  md:hover:bg-transparent
                  md:border-0
                  md:hover:text-blue-700
                  md:p-0
                  dark:text-gray-400
                  md:dark:hover:text-white
                  dark:hover:bg-gray-700 dark:hover:text-white
                  md:dark:hover:bg-transparent
                  font-bold
                  text-lg
                "
                >Contact</a
              >
            </li>
          </ul>
        </div>
        <div class="ml-12">
          
      
          <button
          style="width: 160px"
            type="button"
            class="
              text-white
              bg-[#C3AEA2]
              hover:bg-gradient-to-bl
              focus:ring-4 focus:outline-none focus:ring-green-200
              dark:focus:ring-green-800
              font-medium
              rounded-full
              text-sm
              px-5
              py-3
              text-center
              mb-2
            "
          >
            Register
          </button>
              <!-- <button
            type="button"
            class="
              mr-2
              text-gray-900
              bg-transparent
              hover:bg-gradient-to-bl
              focus:ring-4 focus:outline-none focus:ring-red-100
              dark:focus:ring-red-400
              font-medium
              rounded-lg
              text-sm
              px-5
              py-3.5
              text-center
              mb-2
              font-bold
              text-xl
            "
          >
            Login
          </button> -->

        </div>
      </div>
    </nav>
  </div>
</template>

<script setup></script>

<style></style>
