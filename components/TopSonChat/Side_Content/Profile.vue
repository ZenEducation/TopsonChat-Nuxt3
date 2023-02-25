<template>
  <!-- BEGIN: Side Content Profile -->
  <div
    class="side-content col-span-12 xl:col-span-3 -mt-16 xl:mt-0 pt-20 xl:-mr-6 px-6 xl:pt-6 flex-col overflow-hidden"
    data-content="profile"
  >
    <div class="intro-y text-xl font-medium">Profile</div>
    <div class="intro-y box relative px-4 py-6 mt-5">
      <a
        href="javascript:;"
        title="Settings"
        class="text-gray-600 tooltip w-8 h-8 block flex items-center justify-center absolute top-0 right-0 mr-1 mt-1"
      >
        <i data-feather="edit-2" class="w-4 h-4"></i>
      </a>
      <div class="w-20 h-20 mx-auto image-fit">
        <img
          alt="Topson Messenger Tailwind HTML Admin Template"
          class="rounded-full"
          src="@/assets/images/profile-9.jpg"
        />
        <div
          class="bg-green-500 border-white w-3 h-3 absolute right-0 top-0 mt-1 mr-1 rounded-full border-2"
        ></div>
      </div>
      <div class="text-base font-medium text-center mt-3">John Travolta</div>
      <div class="text-gray-600 text-center text-xs uppercase mt-0.5">
        Software Engineer
      </div>
    </div>
    <div class="intro-y box p-4 mt-3">
      <div
        class="border-gray-200 dark:border-dark-5 flex items-center border-b pb-3"
      >
        <div class="">
          <div class="text-gray-600">Country</div>
          <div class="capitalize mt-0.5">New York City, USA</div>
        </div>
        <i data-feather="globe" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
      <div
        class="border-gray-200 dark:border-dark-5 flex items-center border-b py-3"
      >
        <div class="">
          <div class="text-gray-600">Phone</div>
          <div class="mt-0.5">+32 19 23 62 24 34</div>
        </div>
        <i data-feather="mic" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
      <div
        class="border-gray-200 dark:border-dark-5 flex items-center border-b py-3"
      >
        <div class="">
          <div class="text-gray-600">Gender</div>
          <div class="capitalize mt-0.5">male</div>
        </div>
        <i data-feather="mail" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
      <div class="border-gray-200 dark:border-dark-5 flex items-center py-3">
        <div class="">
          <div class="text-gray-600">Email</div>
          <div class="mt-0.5">johntravolta@left4code.com</div>
        </div>
        <i data-feather="mail" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
    </div>
    <div class="intro-y box p-4 mt-3">
      <div
        class="border-gray-200 dark:border-dark-5 flex items-center border-b pb-3"
      >
        <div class="">
          <div class="text-gray-600">Twitter</div>
          <a class="mt-0.5" href="">@johntravolta</a>
        </div>
        <i data-feather="twitter" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
      <div
        class="border-gray-200 dark:border-dark-5 flex items-center border-b py-3"
      >
        <div class="">
          <div class="text-gray-600">Facebook</div>
          <a class="mt-0.5" href="">johntravolta</a>
        </div>
        <i data-feather="facebook" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
      <div class="border-gray-200 dark:border-dark-5 flex items-center py-3">
        <div class="">
          <div class="text-gray-600">Instagram</div>
          <a class="mt-0.5" href="">@johntravolta</a>
        </div>
        <i data-feather="instagram" class="w-4 h-4 text-gray-600 ml-auto"></i>
      </div>
    </div>
  </div>
  <!-- END: Side Content Profile -->
</template>

<script setup>
</script>

<style lang="scss" scoped>
</style>