<template>
  <div class="flex h-screen">
    <nav-bar></nav-bar>
    <div class="flex1 flex flex-col overflow-x-hidden flex-grow">
      <div class="flex justify-between m-8">
        <div class="text-left">
          <h4 class="font-bold">Orders</h4>
          28 orders found
        </div>
        <div class="flex flex-row items-center">

          <div class="mr-2">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                 xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path>
            </svg>
          </div>

          <div class="mr-8">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                 xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
            </svg>
          </div>
          <div class="mr-1">
            <img class="w-10 h-10 rounded-full" src="https://randomuser.me/api/portraits/men/42.jpg" alt="">
          </div>
          <div class="">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                 xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
            </svg>
          </div>
        </div>
      </div>

      <div class="flex flex-row ml-8">
        <div class="mr-4 active">All Orders</div>
        <div class="mr-4">Dispatch</div>
        <div class="mr-4">Pending</div>
        <div class="mr-4">Completed</div>
      </div>

      <div class="flex flex-row items-center justify-end">
        <div class="w-64 text-left">
          <div class="relative">
            <div class="absolute top-0 left-0 px-3 py-2">
              <svg class="h-6 w-6 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"/>
              </svg>
            </div>

            <input type="text" readonly
                   class="w-full pl-4 pl-10 py-3 leading-none bg-gray-100 rounded-lg shadow-sm focus:outline-none focus:shadow-outline font-medium"
                   placeholder="31 july 2020">

          </div>
        </div>
        <div class="mr-1 ml-1">
          <h1 class="font-semibold">To</h1>
        </div>
        <div class="w-64 text-left">
          <div class="relative">
            <div class="absolute top-0 left-0 px-3 py-2">
              <svg class="h-6 w-6 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"/>
              </svg>
            </div>

            <input type="text" readonly
                   class="w-full pl-4 pl-10 py-3 leading-none bg-gray-100 rounded-lg shadow-sm focus:outline-none focus:shadow-outline font-medium"
                   placeholder="30 july 2020">

          </div>
        </div>
      </div>

      <div class="m-8">
        <table class="w-full flex flex-row flex-no-wrap sm:bg-white overflow-hidden my-5">
          <thead class="">

          <tr class="bg-teal-400 flex flex-col flex-no wrap sm:table-row rounded-l-lg sm:rounded-none mb-2 sm:mb-0">
            <th class="p-3 text-left">#</th>
            <th class="p-3 text-left">Name</th>
            <th class="p-3 text-left">Address</th>
            <th class="p-3 text-left">Price</th>
            <th class="p-3 text-left">Date</th>
            <th class="p-3 text-left">Status</th>
            <th class="p-3 text-left">Actions</th>
          </tr>
          <tr class="bg-teal-400 flex flex-col flex-no wrap sm:table-row rounded-l-lg sm:rounded-none mb-2 sm:mb-0">
            <th class="p-3 text-left">#</th>
            <th class="p-3 text-left">Name</th>
            <th class="p-3 text-left">Address</th>
            <th class="p-3 text-left">Price</th>
            <th class="p-3 text-left">Date</th>
            <th class="p-3 text-left">Status</th>
            <th class="p-3 text-left">Actions</th>
          </tr>
          <tr class="bg-teal-400 flex flex-col flex-no wrap sm:table-row rounded-l-lg sm:rounded-none mb-2 sm:mb-0">
            <th class="p-3 text-left">#</th>
            <th class="p-3 text-left">Name</th>
            <th class="p-3 text-left">Address</th>
            <th class="p-3 text-left">Price</th>
            <th class="p-3 text-left">Date</th>
            <th class="p-3 text-left">Status</th>
            <th class="p-3 text-left">Actions</th>
          </tr>
          <tr class="bg-teal-400 flex flex-col flex-no wrap sm:table-row rounded-l-lg sm:rounded-none mb-2 sm:mb-0">
            <th class="p-3 text-left">#</th>
            <th class="p-3 text-left">Name</th>
            <th class="p-3 text-left">Address</th>
            <th class="p-3 text-left">Price</th>
            <th class="p-3 text-left">Date</th>
            <th class="p-3 text-left">Status</th>
            <th class="p-3 text-left">Actions</th>
          </tr>

          <tr class="bg-teal-400 flex flex-col flex-no wrap sm:table-row rounded-l-lg sm:rounded-none mb-2 sm:mb-0">
            <th class="p-3 text-left">#</th>
            <th class="p-3 text-left">Name</th>
            <th class="p-3 text-left">Address</th>
            <th class="p-3 text-left">Price</th>
            <th class="p-3 text-left">Date</th>
            <th class="p-3 text-left">Status</th>
            <th class="p-3 text-left">Actions</th>
          </tr>
          </thead>
          <tbody class="flex-1 sm:flex-none">

          <tr class="h-5"></tr>

          <tr class="flex flex-col flex-no border wrap sm:table-row mb-2 sm:mb-0 hover:bg-blue-500 hover:text-white hover:absolute hover:z-10 hover:shadow-2xl">
            <td class="border-grey-light p-3">#2598</td>
            <td class="border-grey-light p-3">John Covv</td>
            <td class="border-grey-light p-3">202, Hayle, UK</td>
            <td class="border-grey-light p-3">$25.00</td>
            <td class="border-grey-light p-3">21 july 2020</td>
            <td class="border-grey-light p-3">Pending</td>
            <td class="border-grey-light p-3">
              Delete
            </td>
          </tr>

          <tr class="h-5"></tr>

          <tr class="flex flex-col flex-no border wrap sm:table-row mb-2 sm:mb-0 hover:bg-blue-600 hover:text-white hover:absolute hover:z-10 hover:shadow-2xl">
            <td class="border-grey-light p-3">#2598</td>
            <td class="border-grey-light p-3">John Covv</td>
            <td class="border-grey-light p-3">202, Hayle, UK</td>
            <td class="border-grey-light p-3">$25.00</td>
            <td class="border-grey-light p-3">21 july 2020</td>
            <td class="border-grey-light p-3">Pending</td>
            <td class="border-grey-light p-3">
              Delete
            </td>
          </tr>

          <tr class="h-5"></tr>

          <tr class="flex flex-col flex-no border wrap sm:table-row mb-2 sm:mb-0 hover:bg-blue-600 hover:text-white hover:absolute hover:z-10 hover:shadow-2xl">
            <td class="border-grey-light p-3">#2598</td>
            <td class="border-grey-light p-3">John Covv</td>
            <td class="border-grey-light p-3">202, Hayle, UK</td>
            <td class="border-grey-light p-3">$25.00</td>
            <td class="border-grey-light p-3">21 july 2020</td>
            <td class="border-grey-light p-3">Pending</td>
            <td class="border-grey-light p-3">
              Delete
            </td>
          </tr>

          <tr class="h-5"></tr>

          <tr class="flex flex-col flex-no border wrap sm:table-row mb-2 sm:mb-0 hover:bg-blue-600 hover:text-white hover:absolute hover:z-10 hover:shadow-2xl">
            <td class="border-grey-light p-3">#2598</td>
            <td class="border-grey-light p-3">John Covv</td>
            <td class="border-grey-light p-3">202, Hayle, UK</td>
            <td class="border-grey-light p-3">$25.00</td>
            <td class="border-grey-light p-3">21 july 2020</td>
            <td class="border-grey-light p-3">Pending</td>
            <td class="border-grey-light p-3">
              Delete
            </td>
          </tr>
          </tbody>
        </table>

        <div class="hidden sm:flex-1 sm:flex sm:items-center sm:justify-between">
          <div>
            <p class="text-sm text-gray-700">
              Showing
              <span class="font-medium">1</span>
              to
              <span class="font-medium">10</span>
              of
              <span class="font-medium">97</span>
              results
            </p>
          </div>
          <div>
            <nav class="relative z-0 inline-flex shadow-sm -space-x-px" aria-label="Pagination">
              <a href="#"
                 class="relative inline-flex items-center px-2 py-2 rounded-l-md border border-gray-300 bg-white text-sm font-medium text-gray-500 hover:bg-gray-50">
                <span class="sr-only">Previous</span>
                <!-- Heroicon name: chevron-left -->
                <svg class="h-5 w-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
                     aria-hidden="true">
                  <path fill-rule="evenodd"
                        d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z"
                        clip-rule="evenodd"/>
                </svg>
              </a>
              <a href="#"
                 class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">
                1
              </a>
              <a href="#"
                 class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">
                2
              </a>
              <a href="#"
                 class="hidden md:inline-flex relative items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">
                3
              </a>
              <span
                  class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700">
          ...
        </span>
              <a href="#"
                 class="hidden md:inline-flex relative items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">
                8
              </a>
              <a href="#"
                 class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">
                9
              </a>
              <a href="#"
                 class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">
                10
              </a>
              <a href="#"
                 class="relative inline-flex items-center px-2 py-2 rounded-r-md border border-gray-300 bg-white text-sm font-medium text-gray-500 hover:bg-gray-50">
                <span class="sr-only">Next</span>
                <!-- Heroicon name: chevron-right -->
                <svg class="h-5 w-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
                     aria-hidden="true">
                  <path fill-rule="evenodd"
                        d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                        clip-rule="evenodd"/>
                </svg>
              </a>
            </nav>
          </div>
        </div>

      </div>

    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar";

export default {
  name: 'Home',
  components: {NavBar}
}
</script>

<style>
.active {
  @apply border-b-2 border-blue-600;
}

.selected {
  @apply z-50 bg-red-500 mt-10;
}

@media (min-width: 640px) {
  table {
    display: inline-table !important;
  }

  thead tr:not(:first-child) {
    display: none;
  }
}

td:not(:last-child) {
  border-bottom: 0;
}

th:not(:last-child) {
  border-bottom: 2px solid rgba(0, 0, 0, .1);
}

</style>
