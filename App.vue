<template>
  <section>
    <!-- Main header -->
    <!-- <div
    class="container
    bg-slate-600
    mx-auto
    mt-2
    border-2
    border-gray-700
    rounded-xl
    flex
    justify-between
    "> -->
    <!-- image column -->
    <!-- <div>
      <img src="" alt="hereweGO">
    </div> -->

    <!-- header content -->
    <!-- <div class="flex">
    <div class="px-2 py-2 bg-red-400 mx-1">box</div>
    <div class="px-2 py-2 bg-red-400 mx-1">box</div>
    <div class="px-2 py-2 bg-red-400 mx-1">box</div>
    <div class="px-2 py-2 bg-red-400 mx-1">box</div>
    <div class="px-2 py-2 bg-red-400 mx-1">box</div>
    </div> -->

    <!--  profile icon -->
    <!-- <div clas="">
    Hammas
  </div>
    </div> -->

    <div>
      <nav
        class="bg-white border-gray-200 px-2 md:px-4 py-2.5 rounded-b-xl dark:bg-indigo-900"
      >
        <div
          class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl"
        >
          <a href="" class="flex items-center">
            <!-- <img
              src="assets/images/jobspoLogo.png"
              class="mr-3 h-6 sm:h-9"
              alt="JobSpot Logo"
            /> -->
            <span
              class="self-center text-xl font-semibold whitespace-nowrap dark:text-white"
              >JobSpot</span
            >
          </a>
          <div class="flex items-center md:order-2">
            <a
              href="#"
              class="text-gray-800 dark:text-white hover:bg-gray-50 focus:ring-4 focus:ring-gray-300 font-medium rounded-lg text-sm px-4 py-2 md:px-5 md:py-2.5 mr-1 md:mr-2 dark:hover:dark:bg-indigo-700 focus:outline-none dark:focus:ring-gray-800"
              >Login</a
            >
            <a
              href="#"
              class="text-white dark:bg-indigo-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 md:px-5 md:py-2.5 mr-1 md:mr-2 dark:bg-blue-600 dark:hover:bg-white dark:hover:text-gray-800 transition-all focus:outline-none dark:focus:ring-blue-800"
              >Sign up</a
            >
            <button
              data-collapse-toggle="mega-menu"
              type="button"
              class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
              aria-controls="mega-menu"
              aria-expanded="false"
            >
              <span class="sr-only">Open main menu</span>
              <svg
                aria-hidden="true"
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
            </button>
          </div>
          <div
            id="mega-menu"
            class="hidden justify-between items-center w-full text-sm md:flex md:w-auto md:order-1"
          >
            <ul
              class="flex flex-col mt-4 font-medium md:flex-row md:space-x-8 md:mt-0"
            >
              <li>
                <a
                  href="#"
                  class="block py-2 pr-4 pl-3 text-blue-600 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-600 md:p-0 dark:text-blue-500 md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-blue-500 md:dark:hover:bg-transparent dark:border-gray-700"
                  aria-current="page"
                  >Home</a
                >
              </li>
              <li>
                <button
                  id="mega-menu-dropdown-button"
                  data-dropdown-toggle="mega-menu-dropdown"
                  class="flex justify-between items-center py-2 pr-4 pl-3 w-full font-medium text-gray-700 border-b border-gray-100 md:w-auto hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-600 md:p-0 dark:text-gray-400 md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-blue-500 md:dark:hover:bg-transparent dark:border-gray-700"
                >
                  Company
                </button>
                <div
                  id="mega-menu-dropdown"
                  class="grid hidden absolute z-10 grid-cols-2 w-auto text-sm bg-white rounded-lg border border-gray-100 shadow-md dark:border-gray-700 md:grid-cols-3 dark:bg-gray-700"
                  style="
                    position: absolute;
                    inset: 0px auto auto 0px;
                    margin: 0px;
                    transform: translate(0px, 352px);
                  "
                  data-popper-reference-hidden=""
                  data-popper-escaped=""
                  data-popper-placement="bottom"
                >
                  <div class="p-4 pb-0 text-gray-900 md:pb-4 dark:text-white">
                    <ul class="space-y-4">
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          Blog
                        </a>
                      </li>
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          Newsletter
                        </a>
                      </li>
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          Playground
                        </a>
                      </li>
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          License
                        </a>
                      </li>
                    </ul>
                  </div>
                  <div class="p-4 text-gray-900 dark:text-white">
                    <ul class="space-y-4">
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          Contact Us
                        </a>
                      </li>
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          Support Center
                        </a>
                      </li>
                      <li>
                        <a
                          href="#"
                          class="text-gray-500 dark:text-gray-400 hover:text-blue-600 dark:hover:text-blue-500"
                        >
                          Terms
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
              </li>
              <li>
                <a
                  href="#"
                  class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-600 md:p-0 dark:text-gray-400 md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-blue-500 md:dark:hover:bg-transparent dark:border-gray-700"
                  >Team</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-600 md:p-0 dark:text-gray-400 md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-blue-500 md:dark:hover:bg-transparent dark:border-gray-700"
                  >Contact</a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>

    <div class="container flex justify-center flex-col items-center">
      
      <div class="conainer mx-4 py-4">
        <h2 class="text-7xl font-extrabold dark:text-gray-800 text-center">
        LET'S INSPIRE NATION
        </h2>
        <p class="my-4 text-lg text-gray-500 text-center">
          We have figured out best solution for usability of our project for ease of use and learning from it by integrating best User-Experience. If we discuss about our User interfaces, it would be made with soothing colors that would be added according to the principles of the design and it would be Eye-travelling in design that will enable the users to maintain their interest.
        </p>
       
      </div>
      <img src="assets/images/poster.png" alt="" class="w-4/6 h-1/4 border-gray-900 border-b-8">
    </div>
  </section>
</template>

<script>
export default {
  name: "App",
};
</script>
