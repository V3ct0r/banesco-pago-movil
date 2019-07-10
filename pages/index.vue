<template>
  <!-- <div class="w-3/4 px-4 py-12 max-w-xl mx-auto bg-white rounded-lg shadow-lg"> -->
  <div class="flex w-full h-screen items-center justify-center">
    <div class="w-3/4 flex flex-col px-4 py-6 bg-white rounded-lg shadow-lg">
      <div class="flex items-center justify-center mb-8 tracking-tighter">
        <h2 class="text-blue-800 text-4xl font-black text-xs">
          Banesco
        </h2>
        <h2 class="pl-3 text-green-700 text-4xl font-serif">
          Pago Móvil
        </h2>
      </div>
      <form action="">
        <!-- <div class="flex items-center justify-center"> -->
        <div class="mb-6">
          <input
            class="p-3 border-4 border-gray-700 rounded-lg w-full"
            type="text"
            placeholder="Usuario"
          />
        </div>
        <div class="mb-6">
          <input
            class="p-3 border-4 border-gray-700 rounded-lg w-full"
            type="password"
            placeholder="Clave"
          />
        </div>
        <!-- </div> -->
        <a
          class="flex items-center justify-center p-3 mb-6 bg-green-700 text-white uppercase rounded"
          href=""
        >
          iniciar sesión
        </a>
        <div class="flex items-center justify-center mb-4 text-center">
          <a
            class="w-full w-1/2 p-3 uppercase border-2 border-green-700 rounded"
            href=""
          >
            consultar saldo
          </a>
          <a
            class="w-full w-1/2 ml-4 p-3 uppercase border-2 border-green-700 rounded"
            href=""
          >
            pagar
          </a>
        </div>
        <div>
          <a href="">información</a>
          <a href="">conáctanos</a>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  head: {
    bodyAttrs: {
      class: 'antialiased bg-green-700'
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
