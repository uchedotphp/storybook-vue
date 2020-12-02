<template>
  <div class="grid container mx-auto justify-between">
    <div class="flex items-center">
      <img src="./../assets/imgs/logo.png" class="h-14" alt="" srcset="" />
      <div class="font-bold leading-none">

      <p class="">
        Learn <br />
        at home
        </p>
        <small class="text-xs">this is the slogan below</small>
      </div>
    </div>

    <div class="bg-red-700 flex items-center">
      <div class="bg-white w-9/12 relative p-2 rounded-full">
        <input
          type="text"
          class="w-full pl-6 placeholder-black"
          placeholder="Search for course"
        />
        <svg
          height="24"
          xmlns="http://www.w3.org/2000/svg"
          class="ionicon absolute top-2 right-3"
          viewBox="0 0 512 512"
        >
          <title>Search</title>
          <path
            d="M221.09 64a157.09 157.09 0 10157.09 157.09A157.1 157.1 0 00221.09 64z"
            fill="none"
            stroke="currentColor"
            stroke-miterlimit="10"
            stroke-width="32"
          />
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-miterlimit="10"
            stroke-width="32"
            d="M338.29 338.29L448 448"
          />
        </svg>
      </div>
      <svg
        height="28"
        xmlns="http://www.w3.org/2000/svg"
        class="ionicon ml-2"
        viewBox="0 0 512 512"
      >
        <title>Cart</title>
        <circle
          cx="176"
          cy="416"
          r="16"
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="32"
        />
        <circle
          cx="400"
          cy="416"
          r="16"
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="32"
        />
        <path
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="32"
          d="M48 80h64l48 272h256"
        />
        <path
          d="M160 288h249.44a8 8 0 007.85-6.43l28.8-144a8 8 0 00-7.85-9.57H128"
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="32"
        />
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style lang="scss" scoped>
.grid {
  grid-template-columns: 30% auto;
}
</style>