<script setup></script>

<template>
  <section id="register-form">
    <div class="max-w-7xl mx-auto pb-24 sm:px-6 lg:px-8">
      <h2 class="mx-auto text-xl md:text-3xl font-medium text-center">
        Inscríbete para recibir la primera versión y ayúdanos a crear
        <span class="underline decoration-wavy text-green-600 italic"
          >tu solución ideal</span
        >
      </h2>
      <div class="max-w-2xl mx-auto sm:rounded-md overflow-hidden shadow mt-12">
        <form
          name="contact"
          method="post"
          class="mx-auto p-10 space-y-4 bg-white"
          data-netlify="true"
          data-netlify-honeypot="bot-field"
        >
          <input type="hidden" name="contact" value="contact" />

          <!-- Name -->
          <div>
            <label for="name" class="block text-sm font-medium text-gray-700"
              >Nombre</label
            >
            <div class="mt-1">
              <input
                type="text"
                name="name"
                id="name"
                class="shadow-sm focus:ring-green-500 focus:border-green-500 block w-full sm:text-sm border-gray-300 rounded-md"
                placeholder="Manuel"
              />
            </div>
          </div>

          <!-- Lastname -->
          <div>
            <label
              for="last-name"
              class="block text-sm font-medium text-gray-700"
              >Apellido</label
            >
            <div class="mt-1">
              <input
                type="text"
                name="last-name"
                id="last-name"
                class="shadow-sm focus:ring-green-500 focus:border-green-500 block w-full sm:text-sm border-gray-300 rounded-md"
                placeholder="Perez"
              />
            </div>
          </div>

          <!-- Email -->
          <div>
            <label for="email" class="block text-sm font-medium text-gray-700"
              >Correo</label
            >
            <div class="mt-1">
              <input
                type="email"
                name="email"
                id="email"
                class="shadow-sm focus:ring-green-500 focus:border-green-500 block w-full sm:text-sm border-gray-300 rounded-md"
                placeholder="correo@ejemplo.com"
              />
            </div>
          </div>

          <fieldset>
            <div>
              <legend class="text-base font-medium text-gray-900">
                Usuario
              </legend>
              <p class="text-sm text-gray-500"></p>
            </div>
            <div class="mt-4 space-y-4">
              <div class="flex items-center">
                <input
                  id="pacient"
                  name="pacient"
                  type="radio"
                  class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300"
                />
                <label
                  for="pacient"
                  class="ml-3 block text-sm font-medium text-gray-700"
                >
                  Soy paciente
                </label>
              </div>
              <div class="flex items-center">
                <input
                  id="nutri"
                  name="pacient"
                  type="radio"
                  class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300"
                />
                <label
                  for="nutri"
                  class="ml-3 block text-sm font-medium text-gray-700"
                >
                  Soy nutri
                </label>
              </div>
            </div>
          </fieldset>

          <div class="flex justify-end pt-4">
            <button
              type="submit"
              class="px-4 py-2 rounded-md bg-green-600 hover:bg-green-700 text-white"
            >
              Registrarme
            </button>
          </div>
        </form>
      </div>
    </div>
  </section>
</template>
