<template>
  <div class="w-full min-h-screen p-5 md:p-20 flex items-center justify-center">
    <div class="intro-y auth">
      <img
        class="intro-y mx-auto w-16"
        alt="Topson Messenger Tailwind HTML Admin Template"
        src="@/assets/images/logo.svg"
      />
      <div
        class="intro-y text-gray-700 dark:text-gray-300 text-2xl font-medium text-center mt-16"
      >
        Login to Your Account!
      </div>
      <div class="intro-y box px-5 py-8 mt-8">
        <div class="intro-y">
          <input
            type="text"
            class="form-control py-3 px-4 auth__input intro-y"
            placeholder="Email"
          />
          <input
            type="password"
            class="form-control py-3 px-4 auth__input intro-y mt-4"
            placeholder="Password"
          />
        </div>
        <div
          class="intro-y text-gray-600 dark:text-gray-300 flex text-xs sm:text-sm mt-4"
        >
          <div class="flex items-center mr-auto">
            <input
              type="checkbox"
              class="form-check-input border mr-2"
              id="remember-me"
            />
            <label class="cursor-pointer select-none" for="remember-me"
              >Remember me</label
            >
          </div>
          <a href="">Forgot Password?</a>
        </div>
        <div class="intro-y mt-5 xl:mt-8 text-center xl:text-left">
          <button class="btn btn-primary intro-y w-full xl:mr-3">Login</button>
          <button class="btn btn-outline-secondary intro-y w-full mt-3">
            Sign up
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
</style>