<template>
  <!-- BEGIN: Top Bar -->
  <div class="top-bar top-0 left-0 fixed w-full h-16">
    <div
      class="-intro-y top-bar__content bg-white border-theme-3 dark:bg-dark-2 dark:border-dark-2 border-b w-full h-full flex px-5"
    >
      <!-- BEGIN: Logo -->
      <a class="hidden md:flex items-center h-full mr-auto" href="../dashboard">
        <img
          alt="Topson Messenger Tailwind HTML Admin Template"
          class="h-8"
          src="@/assets/images/logo.svg"
        />
        <div class="text-base font-light ml-4">
          <span class="font-medium">Topson</span> Messenger
        </div>
      </a>
      <!-- END: Logo -->
      <a
        class="mobile-menu-toggler flex md:hidden items-center h-full mr-auto px-5 -ml-5"
        href="javascript:;"
      >
        <i data-feather="bar-chart-2" class="w-5 h-5 transform rotate-90"></i>
      </a>
      <div class="h-full flex items-center">
        <div class="mr-3">Dark Mode</div>
        <input
          @click="($event) => toggleDark()"
          class="form-check-switch"
          type="checkbox"
          id="dark-mode-switcher"
        />
      </div>
      <div class="hidden md:flex items-center px-5">
        <a
          href="javascript:;"
          data-toggle="modal"
          data-target="#invite-friends-modal"
          class="btn btn-primary"
          >Invite Friends</a
        >
      </div>
      <!-- BEGIN: Notifications -->
      <div class="notification-dropdown dropdown">
        <a
          href="javascript:;"
          class="notification-dropdown__toggler text-gray-600 border-theme-7 dark:border-dark-4 dark:text-gray-300 dropdown-toggle h-full flex items-center px-5 relative -mr-3 md:mr-0 md:border-l md:border-r"
        >
          <div class="relative">
            <i data-feather="bell" class="w-5 h-5"></i>
            <div
              class="w-2 h-2 bg-theme-1 text-white flex items-center justify-center absolute -mt-0.5 top-0 right-0 rounded-full"
            ></div>
          </div>
        </a>
        <div class="notification-dropdown__content dropdown-menu">
          <div class="dropdown-menu__content box dark:bg-dark-2 px-4 pt-4 pb-5">
            <div class="text-base font-medium leading-tight mb-4">
              Notifications
            </div>
            <div class="cursor-pointer relative flex items-center">
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-1.jpg"
                />
                <div
                  class="w-3 h-3 absolute right-0 bottom-0 bg-theme-1 border-white rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <div class="flex items-center">
                  <a href="javascript:;" class="font-medium truncate mr-5"
                    >Keanu Reeves</a
                  >
                  <div
                    class="text-opacity-50 text-gray-800 text-xs ml-auto whitespace-nowrap -mt-0.5"
                  >
                    05:09 AM
                  </div>
                </div>
                <div
                  class="text-opacity-70 text-gray-800 dark:text-gray-500 w-full truncate mt-0.5"
                >
                  There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomi
                </div>
              </div>
            </div>
            <div class="cursor-pointer relative flex items-center mt-6">
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-10.jpg"
                />
                <div
                  class="w-3 h-3 absolute right-0 bottom-0 bg-theme-1 border-white rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <div class="flex items-center">
                  <a href="javascript:;" class="font-medium truncate mr-5"
                    >Leonardo DiCaprio</a
                  >
                  <div
                    class="text-opacity-50 text-gray-800 text-xs ml-auto whitespace-nowrap -mt-0.5"
                  >
                    01:10 PM
                  </div>
                </div>
                <div
                  class="text-opacity-70 text-gray-800 dark:text-gray-500 w-full truncate mt-0.5"
                >
                  It is a long established fact that a reader will be distracted
                  by the readable content of a page when looking at its layout.
                  The point of using Lorem
                </div>
              </div>
            </div>
            <div class="cursor-pointer relative flex items-center mt-6">
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-14.jpg"
                />
                <div
                  class="w-3 h-3 absolute right-0 bottom-0 bg-theme-1 border-white rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <div class="flex items-center">
                  <a href="javascript:;" class="font-medium truncate mr-5"
                    >Christian Bale</a
                  >
                  <div
                    class="text-opacity-50 text-gray-800 text-xs ml-auto whitespace-nowrap -mt-0.5"
                  >
                    05:09 AM
                  </div>
                </div>
                <div
                  class="text-opacity-70 text-gray-800 dark:text-gray-500 w-full truncate mt-0.5"
                >
                  It is a long established fact that a reader will be distracted
                  by the readable content of a page when looking at its layout.
                  The point of using Lorem
                </div>
              </div>
            </div>
            <div class="cursor-pointer relative flex items-center mt-6">
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-4.jpg"
                />
                <div
                  class="w-3 h-3 absolute right-0 bottom-0 bg-theme-1 border-white rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <div class="flex items-center">
                  <a href="javascript:;" class="font-medium truncate mr-5"
                    >Kevin Spacey</a
                  >
                  <div
                    class="text-opacity-50 text-gray-800 text-xs ml-auto whitespace-nowrap -mt-0.5"
                  >
                    06:05 AM
                  </div>
                </div>
                <div
                  class="text-opacity-70 text-gray-800 dark:text-gray-500 w-full truncate mt-0.5"
                >
                  There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomi
                </div>
              </div>
            </div>
            <div class="cursor-pointer relative flex items-center mt-6">
              <div class="w-10 h-10 flex-none image-fit mr-1">
                <img
                  alt="Topson Messenger Tailwind HTML Admin Template"
                  class="rounded-full"
                  src="@/assets/images/profile-13.jpg"
                />
                <div
                  class="w-3 h-3 absolute right-0 bottom-0 bg-theme-1 border-white rounded-full border-2"
                ></div>
              </div>
              <div class="ml-2 overflow-hidden">
                <div class="flex items-center">
                  <a href="javascript:;" class="font-medium truncate mr-5"
                    >Tom Hanks</a
                  >
                  <div
                    class="text-opacity-50 text-gray-800 text-xs ml-auto whitespace-nowrap -mt-0.5"
                  >
                    05:09 AM
                  </div>
                </div>
                <div
                  class="text-opacity-70 text-gray-800 dark:text-gray-500 w-full truncate mt-0.5"
                >
                  There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomi
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- END: Notifications -->
      <!-- BEGIN: Account -->
      <div class="account-dropdown dropdown relative">
        <a
          href="javascript:;"
          class="h-full dropdown-toggle flex items-center pl-5"
        >
          <div class="w-8 h-8 image-fit">
            <img
              alt="Topson Messenger Tailwind HTML Admin Template"
              class="rounded-full shadow-md"
              src="@/assets/images/profile-14.jpg"
            />
          </div>
          <div class="hidden md:block ml-3">
            <div class="w-28 truncate font-medium leading-tight">
              Keanu Reeves
            </div>
            <div class="account-dropdown__info text-xs text-gray-600">
              Frontend Engineer
            </div>
          </div>
        </a>
        <div
          class="dropdown-content dropdown-menu absolute w-56 top-0 right-0 z-20"
        >
          <div class="dropdown-menu__content box dark:bg-dark-2">
            <div class="p-2">
              <a
                href=""
                class="flex items-center block p-2 transition duration-300 ease-in-out rounded-md hover:bg-gray-200 dark:hover:bg-dark-3"
              >
                <i data-feather="user" class="w-4 h-4 mr-2"></i> Profile
              </a>
              <a
                href=""
                class="flex items-center block p-2 transition duration-300 ease-in-out rounded-md hover:bg-gray-200 dark:hover:bg-dark-3"
              >
                <i data-feather="edit" class="w-4 h-4 mr-2"></i> Add Account
              </a>
              <a
                href=""
                class="flex items-center block p-2 transition duration-300 ease-in-out rounded-md hover:bg-gray-200 dark:hover:bg-dark-3"
              >
                <i data-feather="lock" class="w-4 h-4 mr-2"></i> Reset Password
              </a>
              <a
                href=""
                class="flex items-center block p-2 transition duration-300 ease-in-out rounded-md hover:bg-gray-200 dark:hover:bg-dark-3"
              >
                <i data-feather="help-circle" class="w-4 h-4 mr-2"></i> Help
              </a>
            </div>
            <div class="border-gray-200 dark:border-dark-4 p-2 border-t">
              <a
                href=""
                class="flex items-center block p-2 transition duration-300 ease-in-out rounded-md hover:bg-gray-200 dark:hover:bg-dark-3"
              >
                <i data-feather="toggle-right" class="w-4 h-4 mr-2"></i> Logout
              </a>
            </div>
          </div>
        </div>
      </div>
      <!-- END: Account -->
    </div>
  </div>
  <!-- END: Top Bar -->
</template>

<script setup>
import feather from "feather-icons";
import { onMounted } from "vue";
import { useDark, useToggle } from "@vueuse/core";

//dark mode
const isDark = useDark({
  selector: "body",
  attribute: "class",
  valueDark: "dark",
  valueLight: "light",
});
const toggleDark = useToggle(isDark);
onMounted(() => {
  feather.replace();
});
</script>

<style  scoped>
</style>