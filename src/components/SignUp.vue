<template>
  <div class="py-20 px-40 container mx-auto grid">
    <div>
      <div class="my-6">
        <p class="text-4xl font-bold py-2 leading-none">
          Welcome to
          <span class="block">Learn at home</span>
        </p>
        <small class="">
          If you already have a learning online <br />
          account, please sign in below.
        </small>
      </div>
      <div>
        <form action="">
          <div class="relative">
            <label class="absolute top-1 left-4" for="email">Email</label>
            <input
              type="text"
              id="email"
              placeholder="input your email"
              class="w-full border border-gray-400 border-b-0 px-4 pt-6 pb-2 focus:outline-none"
            />
          </div>
          <div class="relative">
            <label class="absolute top-1 left-4" for="password">Password</label>
            <input
              type="text"
              id="password"
              placeholder="input your password"
              class="w-full border border-gray-400 px-4 pt-6 pb-2 focus:outline-none"
            />
          </div>
          <div class="flex justify-between px-4 py-5">
            <span> Remember me </span>
            <a href="#" class="underline"> Forgot Password? </a>
          </div>
          <button class="bg-gray-300 px-14 py-2 focus:outline-none mr-4">Submit</button>
          <button class="bg-white px-14 py-2 border border-gray-400 focus:outline-none">Sign Up</button>
        </form>
      </div>
    </div>
    <div class="flex justify-end pr-10">
      <div class="rounded-full h-40 w-40 border-4 border-gray-400 relative">
        <div class="rounded-full h-80 w-80 bg-gray-200 absolute right-8 top-14">
          <div class="rounded-full h-32 w-32 bg-gray-500 absolute top-44 right-60"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Signup Component",
};
</script>

<style lang="scss" scoped>
.grid {
  grid-template-columns: 30% auto;
}
</style>