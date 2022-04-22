<template>
  <div>
    <div class="max-w-7xl mx-auto px-4 py-24 sm:px-6 lg:px-8">
      <div class="rounded-2xl px-6 py-16 sm:p-16">
        <div class="max-w-xl mx-auto lg:max-w-none">
          <div class="text-center">
            <h2 class="text-2xl font-extrabold tracking-tight text-gray-900">
              Nuestras principales metas
            </h2>
          </div>
          <div
            class="mt-12 max-w-sm mx-auto grid grid-cols-1 gap-y-10 gap-x-8 sm:max-w-none lg:grid-cols-3"
          >
            <div
              v-for="incentive in incentives"
              :key="incentive.name"
              class="text-center sm:flex sm:text-left lg:block lg:text-center"
            >
              <div class="sm:flex-shrink-0">
                <div class="flow-root">
                  <img
                    class="w-16 h-16 mx-auto"
                    :src="incentive.imageSrc"
                    alt=""
                  />
                </div>
              </div>
              <div class="mt-3 sm:mt-0 sm:ml-6 lg:mt-6 lg:ml-0">
                <h3 class="text-sm font-medium text-gray-900">
                  {{ incentive.name }}
                </h3>
                <p class="mt-2 text-sm text-gray-500">
                  {{ incentive.description }}
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import imgTracking from "../assets/tracking.png";
import imgSalad from "../assets/tracking.png";

const incentives = [
  {
    name: "Seguimiento",
    imageSrc: imgTracking,
    description:
      "¿Recuerdas que comiste hace tres semanas? Te ayudamos a llevar un registro de las porciones de alimentos que consumes. Información accesible por tu nutricionista para una asistencia más eficiente.",
  },
  {
    name: "Metas",
    imageSrc:
      "https://tailwindui.com/img/ecommerce/icons/icon-warranty-simple.svg",
    description:
      "Fija metas en conjunto a tu nutricionista. Avanza paso a paso y ve como tu progreso se transforma en resultados.",
  },
  {
    name: "Alimentos",
    imageSrc: imgSalad,
    description:
      "Toda la información que necesitas: grupos de alimentos y listas de alimentos con sus porciones. Lleva la pauta a dónde sea con tu celular.",
  },
];
</script>
