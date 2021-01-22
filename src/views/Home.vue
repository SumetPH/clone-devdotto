<template>
  <div class="bg-gray-800 text-white">
    <div class="container mx-auto xl:px-36  pt-2">
      <div class="grid grid-cols-4 gap-4">
        <ul class="hidden md:block">
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300" href="#">Home</a>
          </li>
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300" href="#">Reading
              List</a>
          </li>
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300" href="#">Listings</a>
          </li>
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300" href="#">Podcasts</a>
          </li>
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300" href="#">Videos</a>
          </li>
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300" href="#">Tags</a>
          </li>
          <li>
            <a class="inline-block w-full p-2 rounded hover:bg-gray-700 hover:text-purple-300 text-sm"
              href="#">More...</a>
          </li>
        </ul>

        <div class="col-span-4 md:col-span-3 lg:col-span-2">
          <!-- header content -->
          <div class="grid grid-cols-3 mb-3">
            <div class="flex items-center">
              <span class="inline-block font-bold text-xl pl-3 md:pl-0">Posts</span>
            </div>
            <div class="hidden md:block col-span-2 flex justify-end items-center text-gray-300">
              <a class="border-b-2 border-blue-500 p-2" href="#">Feed</a>
              <a class="p-2" href="#">Week</a>
              <a class="p-2" href="#">Month</a>
              <a class="p-2" href="#">Year</a>
              <a class="p-2" href="#">Infinity</a>
              <a class="p-2" href="#">Latest</a>
            </div>
          </div>
          <!-- end header content -->

          <!-- content -->
          <div class="w-full bg-gray-700 mb-2 rounded-lg overflow-hidden">
            <img class="object-cover"
              src="https://res.cloudinary.com/practicaldev/image/fetch/s--M8enUJ3l--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/yb1nc85cjryewmxxsgcd.png"
              alt="">
            <div class="p-5">
              <div class="flex mb-2">
                <div>
                  <img class="w-8 rounded-full"
                    src="https://res.cloudinary.com/practicaldev/image/fetch/s--yLe7MHLr--/c_fill,f_auto,fl_progressive,h_90,q_auto,w_90/https://dev-to-uploads.s3.amazonaws.com/uploads/user/profile_image/429862/46d4537e-4efc-4333-b743-d0f67136bb57.png"
                    alt="">
                </div>
                <div class="ml-2 text-xs text-gray-300">
                  <p>Unnati Bamania </p>
                  <p>Jan 18</p>
                </div>
              </div>
              <div>
                <router-link to="/content" class="font-bold text-3xl mb-2">Some projects to build your resume!
                </router-link>
                <div class="space-x-3 mb-2">
                  <span>#javascript</span>
                  <span>#react</span>
                  <span>#web</span>
                </div>
                <div class="space-x-5">
                  <span>700 reactions</span>
                  <span>600 comments</span>
                </div>
              </div>
            </div>
          </div>

          <div class="w-full bg-gray-700 mb-2 rounded-lg overflow-hidden">
            <div class="p-5">
              <div class="flex mb-2">
                <div>
                  <img class="w-8 rounded-full"
                    src="https://res.cloudinary.com/practicaldev/image/fetch/s--OIZ_tbLk--/c_fill,f_auto,fl_progressive,h_50,q_auto,w_50/https://dev-to-uploads.s3.amazonaws.com/uploads/user/profile_image/137579/7c12095e-3ceb-4e71-9845-79ac31a72dab.jpg                     "
                    alt="">
                </div>
                <div class="ml-2 text-xs text-gray-300">
                  <p>Charlotte Fereday </p>
                  <p>Jan 17</p>
                </div>
              </div>
              <div>
                <p class="font-bold text-3xl mb-2">Authentication and Authorisation 101</p>
                <div class="space-x-3 mb-2">
                  <span>#javascript</span>
                  <span>#react</span>
                  <span>#web</span>
                </div>
                <div class="space-x-5">
                  <span>500 reactions</span>
                  <span>400 comments</span>
                </div>
              </div>
            </div>
          </div>
          <!-- end content -->
        </div>

        <div class="hidden lg:block">
          <div class="bg-gray-700 rounded-md">
            <div class="flex justify-between items-end p-4">
              <span class="text-xl font-bold">Listings</span>
              <a href="#" class="text-sm text-blue-500">See all</a>
            </div>
            <a href="#">
              <div class="hover:bg-gray-800 p-4">
                <p class="mb-1">Build a full-stack role-based auth in 60 mins</p>
                <p class="text-sm">education</p>
              </div>
            </a>
            <a href="#">
              <div class="hover:bg-gray-800 p-4">
                <p class="mb-1">Full-stack role-based authorization in 60 mins</p>
                <p class="text-sm">education</p>
              </div>
            </a>
            <a href="#">
              <div class="hover:bg-gray-800 p-4">
                <p class="mb-1">Free Global Diversity CFP Day virtual workshop on Saturday</p>
                <p class="text-sm">education</p>
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>