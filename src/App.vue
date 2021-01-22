<template>
  <div class="bg-gray-700">
    <div class="container mx-auto text-white py-2 xl:px-36">
      <div class="grid grid-cols-2">
        <div>
          <div class="inline-block py-2 px-1 bg-white rounded text-black">
            <span class="font-bold text-xl">DEV</span>
          </div>
          <input
            class="w-80 hidden md:inline-block bg-gray-600 rounded ml-2 p-2 focus:outline-none focus:ring-2 focus:ring-blue-700"
            type="text" placeholder="Search..." />
        </div>

        <div class="flex justify-end items-center space-x-3">
          <a class="hidden md:inline-block bg-purple-500 rounded p-2 text-black" href="#">Write a post</a>
          <div>
            <svg class="w-8 inline-block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
              stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
            </svg>
          </div>
          <div>
            <svg class="w-8 inline-block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
              stroke="currentColor">
              <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2}
                d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
            </svg>
          </div>
          <div>
            <img class="w-8 rounded-full inline-block"
              src="https://res.cloudinary.com/practicaldev/image/fetch/s---cZ17P-H--/c_fill,f_auto,fl_progressive,h_90,q_auto,w_90/https://dev-to-uploads.s3.amazonaws.com/uploads/user/profile_image/474923/a35b0796-fe23-4a48-b648-6b85781952d4.jpeg"
              alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
  <router-view />
  <div class="bg-gray-800 h-52"></div>
</template>