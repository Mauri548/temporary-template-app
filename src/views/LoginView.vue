<template>
    <div class=" container m-auto h-screen text-white px-5 bg-[url('https://img.freepik.com/vector-gratis/fondo-pantalla-movil-universo-planetas_79603-600.jpg?w=2000')]">
      
      <div class=" py-28">
        <h1 class=" text-8xl font-bold">Logo</h1>
      </div>
      
      <p class=" text-start">Log in</p>
      
      <form action="post">
        <div>
          <input class=" w-full my-2 py-2 pl-3 rounded bg-grey-300 opacity-70 text-black" type="text" name="email" id="email" placeholder="Email">
          <div class="relative">
            <input class=" w-full my-2 py-2 pl-3 rounded bg-grey-300 opacity-70 text-black" type="password" name="password" id="password" placeholder="Password">
            <i class="fa-regular fa-eye absolute top-5 right-5 text-gray-400"></i>
          </div>
        </div>
        <button class=" w-full my-2 rounded-lg py-2 font-bold bg-pink-500">Log In</button>
      </form>
      
      <p class=" text-end text-sm underline">Did yoy forget the password?</p>

      <div class="flex flex-col mt-12">
        <button class="w-full my-2 rounded-lg py-2 font-bold bg-sky-500 opacity-70 relative">
          <i class="fa-brands fa-twitter absolute top-3 left-3"></i>
          Twitter
        </button>
        <button class="w-full my-2 rounded-lg py-2 font-bold bg-indigo-500 opacity-70 relative">
          <i class="fa-brands fa-google absolute top-3 left-3"></i>
          Google
        </button>
      </div>
    
    </div>
</template>

<script>
export default {
  name: 'LoginView'
}
</script>

<style>

</style>