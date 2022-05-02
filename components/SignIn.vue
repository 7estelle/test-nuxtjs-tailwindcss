<template>
  <!-- <Tutorial /> -->
<main class="p-8 bg-indigo-500 h-screen">
    <img src="../assets/medias/goodvest-logo.svg" alt="" class="m-auto pb-8 w-24">
  <div class="grid content-center justify-center max-w-sm w-full m-auto bg-white rounded-md">
    <img src="../assets/medias/sign-in2.png" alt="" class="rounded-t-md">
    <div class="px-8 py-4">
  <h1 class="m-auto text-center mb-4 font-serif italic text-4xl">Sign in</h1>
  <div class="mb-4">
    <label for="user_id" class="inline-block mb-2 font-bold">Username or email</label><br>
    <input id="user_id" type="text" name="user_id" placeholder="Your username or email" class="border-2 border-slate-200 w-full p-2 rounded">
  </div>
  <div>
    <label for="user_pwd" class="inline-block mb-2 font-bold">Password</label><br>
    <input id="user_pwd" type="password" name="user_pwd" placeholder="Your password" class="border-2 border-slate-200 w-full p-2 rounded">
    <a href="#" class="text-indigo-500 block font-bold text-xs">Forgot password?</a>
  </div>
  </div>
  <div class="border-t-2 border-slate-200 px-8 py-4 flex justify-between items-center">
    <p class="inline-block text-xs">Don't have an account? <a href="#" class="text-indigo-500">Sign up</a></p>
    <a href="#" class="bg-indigo-500 px-6 py-1.5 inline-block rounded-md text-white font-bold">Sign in</a>
  </div>
  </div>
</main>
</template>

<script>
export default {
  name: 'SignIn',
}
</script>