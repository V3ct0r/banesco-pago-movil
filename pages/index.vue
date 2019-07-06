<template>
  <div class="w-3/4 px-4 py-12 max-w-xl mx-auto bg-white">
    <div class="flex items-center justify-center mb-8">
      <h2 class="text-blue-800 text-5xl font-black">Banesco</h2>
      <h2 class="text-green-600 text-5xl font-serif">Pago Móvil</h2>
    </div>
    <form action="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
      <!-- <div class="flex items-center justify-center"> -->
      <div class="mb-6">
        <input
          class="border-4 border-gray-500 rounded-lg w-full"
          type="text"
          placeholder="Usuario"
        />
      </div>
      <div class="mb-6">
        <input
          class="border-4 border-gray-500 rounded-lg w-full"
          type="password"
          placeholder="Clave"
        />
      </div>
      <!-- </div> -->
      <a href="">iniciar sesión</a>
      <div>
        <a href="">consultar saldo</a>
        <a href="">pagar</a>
      </div>
      <div>
        <a href="">información</a>
        <a href="">conáctanos</a>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  components: {},
  head: {
    bodyAttrs: {
      class: 'antialiased bg-green-600'
    }
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
