<template>
  <div>
    <div class="flex justify-evenly gap-4 flex-wrap sm:flex-nowrap md:space-x-10 px-12">
      <button
      @click="showToast"
        data-modal-target="Paramecia"
        data-modal-toggle="Paramecia"
        class="block w-full md:w-auto text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        type="button"
      >
        Paramecia
      </button>
      <button
        data-modal-target="zoan"
        data-modal-toggle="zoan"
        class="block w-full md:w-auto text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        type="button"
      >
        Zoan
      </button>
      <button
        data-modal-target="logia"
        data-modal-toggle="logia"
        class="block w-full md:w-auto text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        type="button"
      >
        Logia
      </button>
      <button
        data-modal-target="despertar"
        data-modal-toggle="despertar"
        class="block w-full md:w-auto text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        type="button"
      >
        Despertar
      </button>
      
    </div>
   
    <ul class="flex  border-b-8 border-gray-200 dark:border-gray-700 mt-10 "></ul>


    <!-- Small Modal -->

    <!-- Default Modal -->

    <!-- Large Modal -->
    <div
      id="Paramecia"
      tabindex="-1"
      class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full"
    >
      <div class="relative w-full max-w-4xl max-h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <!-- Modal header -->
          <div
            class="flex items-center justify-between p-5 border-b rounded-t bg-blue-700 dark:border-gray-600"
          >
            <h3 class="text-xl font-medium text-gray-100 dark:text-white">Paramecia</h3>
            <button
              type="button"
              class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
              data-modal-hide="Paramecia"
            >
              <svg
                aria-hidden="true"
                class="w-5 h-5"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="sr-only">Close modal</span>
            </button>
          </div>
          <!-- Modal body -->
          <div class="p-6 space-y-6">
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Es la más común de las tres clases de frutas. Los consumidores de Frutas del Diablo
              paramecia ganan habilidades físicas. Las frutas tipo paramecia poseen la mayor
              cantidad de poderes, mientras que las zoan permiten transformar al consumidor en un
              animal y las logia en un elemento, las paramecia no tienen un poder específico, siendo
              el poder totalmente al azar.
            </p>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Por último, hay algunos consumidores que pueden manipular y generar algunos tipos de
              sustancias muy similar a los logia, pero sólo generan, no pueden controlar la misma
              sustancia si es ajena a su cuerpo.
            </p>
          </div>
          <!-- Modal footer -->
          <div
            class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600"
          >
            <button
              data-modal-hide="Paramecia"
              type="button"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Ok
            </button>
            <button
              data-modal-hide="Paramecia"
              type="button"
              class="text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-200 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 dark:bg-gray-700 dark:text-gray-300 dark:border-gray-500 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-600"
            >
              Cerrar
            </button>
          </div>
        </div>
      </div>
    </div>

    <div
      id="zoan"
      tabindex="-1"
      class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full"
    >
      <div class="relative w-full max-w-4xl max-h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <!-- Modal header -->
          <div
            class="flex items-center justify-between p-5 border-b rounded-t dark:border-gray-600"
          >
            <h3 class="text-xl font-medium text-gray-900 dark:text-white">Zoan</h3>
            <button
              type="button"
              class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
              data-modal-hide="zoan"
            >
              <svg
                aria-hidden="true"
                class="w-5 h-5"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="sr-only">Close modal</span>
            </button>
          </div>
          <!-- Modal body -->
          <div class="p-6 space-y-6">
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Los consumidores de Frutas del Diablo tipo zoan ganan la habilidad de transformarse en
              un animal (y adquieren toda capacidad del animal en que se transforman). El consumidor
              también puede cambiar entre una forma híbrida, a medio camino entre la forma humana y
              la de animal, su forma original y la forma del animal completo. Hay frutas zoan que no
              sólo son animales comunes, también animales prehistóricos y seres mitológicos (las
              zoan prehistóricas con muy raras, pero más aún las zoan mitológicas que son incluso
              más raras que las logia).
            </p>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Según se dice, las frutas zoan son las mejores para luchas cuerpo a cuerpo,
              especialmente las zoan "carnívoras", las cuales son más feroces y fuertes. Una
              curiosidad más de este tipo de fruta es que existe un método desconocido que permite a
              "objetos" "comer" una Fruta del diablo y darles vida.
            </p>
          </div>
          <!-- Modal footer -->
          <div
            class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600"
          >
            <button
              data-modal-hide="zoan"
              type="button"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Ok
            </button>
            <button
              data-modal-hide="zoan"
              type="button"
              class="text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-200 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 dark:bg-gray-700 dark:text-gray-300 dark:border-gray-500 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-600"
            >
              Cerrar
            </button>
          </div>
        </div>
      </div>
    </div>

    <div
      id="logia"
      tabindex="-1"
      class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full"
    >
      <div class="relative w-full max-w-4xl max-h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <!-- Modal header -->
          <div
            class="flex items-center justify-between p-5 border-b rounded-t dark:border-gray-600"
          >
            <h3 class="text-xl font-medium text-gray-900 dark:text-white">Logia</h3>
            <button
              type="button"
              class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
              data-modal-hide="logia"
            >
              <svg
                aria-hidden="true"
                class="w-5 h-5"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="sr-only">Close modal</span>
            </button>
          </div>
          <!-- Modal body -->
          <div class="p-6 space-y-6">
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              La más rara de las tres clases, los consumidores de frutas del diablo logia adquieren
              la capacidad de transformarse en un elemento (haciéndolos intangibles o
              indestructibles). También adquieren todas las habilidades relacionadas con este
              elemento y ganan la habilidad para dispersarse, manipular y unirse a cualquier parte
              de su cuerpo, mientras el consumidor sepa controlar sus poderes y evitar a tiempo los
              ataques (incluyendo heridas de bala, explosiones o cortes).
            </p>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Los consumidores de Frutas del Diablo tipo logia pueden mover todas las partes de sus
              cuerpos transformadas, mientras están en forma de su elemento.
            </p>
          </div>
          <!-- Modal footer -->
          <div
            class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600"
          >
            <button
              data-modal-hide="logia"
              type="button"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Ok
            </button>
            <button
              data-modal-hide="logia"
              type="button"
              class="text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-200 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 dark:bg-gray-700 dark:text-gray-300 dark:border-gray-500 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-600"
            >
              Cerrar
            </button>
          </div>
        </div>
      </div>
    </div>

    <div
      id="despertar"
      tabindex="-1"
      class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full"
    >
      <div class="relative w-full max-w-4xl max-h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <!-- Modal header -->
          <div
            class="flex items-center justify-between p-5 border-b rounded-t dark:border-gray-600"
          >
            <h3 class="text-xl font-medium text-gray-900 dark:text-white">Despertar</h3>
            <button
            @click=""
              type="button"
              class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
              data-modal-hide="despertar"
            >
              <svg
                aria-hidden="true"
                class="w-5 h-5"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="sr-only">Close modal</span>
            </button>
          </div>
          <!-- Modal body -->
          <div class="p-6 space-y-6">
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Los poderes que otorgan las frutas del diablo raramente pueden "despertar" (覚醒,
              kakusei ?) incrementando así las habilidades de su consumidor. Los detalles sobre cómo
              podrían ser despertados las habilidades aún no se conocen, pero se ha visto que
              aumentan significativamente el poder del consumidor y dan nuevas habilidades. El
              efecto del despertar parece depender del tipo de fruta del diablo.

              <br />
              Para las habilidades de tipo zoan, el despertar les otorga transformaciones más
              grandes que otras zoan, además ganan fuerza física y resistencia, así como un tiempo
              de recuperación más corto.
            </p>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
              Para las habilidades de tipo paramecia, el despertar permite que la habilidad que
              otorga una fruta del diablo se pueda expandir al entorno del consumidor, haciendo que
              éste pueda manipular y deformar dicho entorno a voluntad. La diferencia principal
              entre los poderes despertados y las frutas del diablo que afectan al entorno es que no
              se requiere un contacto directo con el entorno y éste puede ser modificado por el
              consumidor con sólo su pensamiento. Aun así, no todas las paramecia tienen el mismo
              despertar, habiendo casos en los que simplemente de aumenta drásticamente su rango de
              efecto.
            </p>
          </div>
          <!-- Modal footer -->
          <div
            class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600"
          >
            <button
              
              data-modal-hide="despertar"
              type="button"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Ok
            </button>
            <button
              data-modal-hide="despertar"
              type="button"
              class="text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-200 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 dark:bg-gray-700 dark:text-gray-300 dark:border-gray-500 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-600"
            >
              Cerrar
            </button>
          </div>
        </div>
      </div>
      
    </div>
    <!-- <button id="miBoton" @click="manejarClick">Haz clic</button> inteto de notificaciones --> 
  </div>

  
</template>

<script >
// intente enviar notificaciones import Toastify from 'toastify-js';
// import 'toastify-js/src/toastify.css';

// export default {
  
//     manejarClick() {
//       Toastify({

// text: "This is a toast",

// duration: 3000

// }).showToast();
//       console.log('Botón clickeado');
//       // Puedes llamar a funciones, realizar acciones, etc.
//     }
//   }


</script>