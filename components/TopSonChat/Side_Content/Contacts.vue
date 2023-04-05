<template>
  <!-- BEGIN: Side Content Contacts -->
  <div
    class="col-span-12 xl:col-span-3 -mt-16 xl:mt-0 pt-20 xl:-mr-6 px-6 xl:pt-6 flex flex-col overflow-hidden"
    data-content="contacts"
  >
    <div class="intro-y text-xl font-medium">Contacts</div>
    <div class="intro-y relative mt-5 mb-6">
      <input
        type="text"
        class="form-control box py-3 px-4 border-transparent pr-8"
        placeholder="Search for contacts..."
      />
      <i
        data-feather="search"
        class="text-gray-600 w-5 h-5 absolute inset-y-0 right-0 my-auto mr-3"
      ></i>
    </div>
    <div class="intro-y overflow-y-auto scrollbar-hidden -mx-5 px-5">
      <div class="user-list">
        <div class="intro-x">
          <div class="intro-x text-gray-500 mb-3">A</div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-9.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">John Travolta</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 26 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a
                  class="dropdown-toggle w-4 h-4"
                  href="javascript:;"
                  aria-expanded="false"
                >
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in mt-4"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-1.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">Brad Pitt</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 59 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a
                  class="dropdown-toggle w-4 h-4"
                  href="javascript:;"
                  aria-expanded="false"
                >
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in mt-4"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-7.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">Leonardo DiCaprio</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 29 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a
                  class="dropdown-toggle w-4 h-4"
                  href="javascript:;"
                  aria-expanded="false"
                >
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x text-gray-500 mt-6 mb-3">B</div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-9.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">John Travolta</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 26 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a class="dropdown-toggle w-4 h-4" href="javascript:;">
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in mt-4"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-1.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">Brad Pitt</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 59 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a class="dropdown-toggle w-4 h-4" href="javascript:;">
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in mt-4"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-7.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">Leonardo DiCaprio</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 29 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a class="dropdown-toggle w-4 h-4" href="javascript:;">
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in mt-4"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-4.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium"
                  >Sylvester Stallone</a
                >
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 42 minutes ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a class="dropdown-toggle w-4 h-4" href="javascript:;">
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x text-gray-500 mt-6 mb-3">C</div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-9.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">John Travolta</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 26 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a class="dropdown-toggle w-4 h-4" href="javascript:;">
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="intro-x block">
            <div
              class="box dark:bg-dark-3 cursor-pointer relative flex items-center px-4 py-3 zoom-in mt-4"
            >
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-1.jpg"
                />
                <div
                  class="bg-green-500 border-white w-3 h-3 absolute right-0 bottom-0 rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <a href="javascript:;" class="font-medium">Brad Pitt</a>
                <div class="flex items-center text-xs mt-0.5">
                  <div class="text-gray-600 dark:text-gray-500 truncate">
                    Last seen 59 seconds ago ago
                  </div>
                </div>
              </div>
              <div
                class="dropdown absolute flex items-center top-0 bottom-0 right-0 mr-4 ml-auto"
              >
                <a class="dropdown-toggle w-4 h-4" href="javascript:;">
                  <i data-feather="more-vertical" class="w-4 h-4"></i>
                </a>
                <div class="dropdown-menu w-40">
                  <div class="dropdown-menu__content box dark:bg-dark-1 p-2">
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="share-2" class="w-4 h-4 mr-2"></i> Share
                      Contact
                    </a>
                    <a
                      href=""
                      class="flex items-center p-2 transition duration-300 ease-in-out bg-white dark:bg-dark-1 hover:bg-gray-200 dark:hover:bg-dark-2 rounded-md"
                    >
                      <i data-feather="copy" class="w-4 h-4 mr-2"></i> Copy
                      Contact
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- END: Side Content Contacts -->
</template>

<script setup>
</script>

<style lang="scss" scoped>
</style>