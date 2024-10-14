<template>
    <div class="p-6">
      <!-- Button to open modal -->
      <button
        @click="openModal"
        class="bg-blue-500 text-white p-4 rounded-md hover:bg-blue-600 transition duration-300"
      >
        Open Modal
      </button>
  
      <!-- Modal Pop-up (fades in and out) -->
      <Transition name="nested" :duration="1000">
        <div
          v-if="showModal"
          class="outer pop-up-outer"
        >
          <div class="inner pop-up-inner">
            <h2 class="text-xl font-semibold mb-4">Modal Title</h2>
            <p class="text-gray-700 mb-6">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis egestas rhoncus.
            </p>
            <button
              @click="closeModal"
              class="bg-red-500 text-white p-2 rounded-md hover:bg-red-600 transition duration-300"
            >
              Close
            </button>
          </div>
        </div>
      </Transition>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        showModal: false,
      };
    },
    methods: {
      openModal() {
        this.showModal = true;
      },
      closeModal() {
        this.showModal = false;
      },
    },
  };
  </script>
  
  <style>
    .nested-enter-active, .nested-leave-active {
    	transition: all 1s ease-in-out;
    }
    /* delay leave of parent element */
    .nested-leave-active {
      transition-delay: 0.5s;
    }
    
    .nested-enter-from,
    .nested-leave-to {
      transform: translateY(30px);
      opacity: 0;
    }
    
    /* we can also transition nested elements using nested selectors */
    .nested-enter-active .inner,
    .nested-leave-active .inner { 
      transition: all 0.5s ease-in-out;
    }
    /* delay enter of nested element */
    .nested-enter-active .inner {
    	transition-delay: 0.5s;
    }
    
    .nested-enter-from .inner,
    .nested-leave-to .inner {
      transform: translateX(30px);
      /*
      	Hack around a Chrome 96 bug in handling nested opacity transitions.
        This is not needed in other browsers or Chrome 99+ where the bug
        has been fixed.
      */
      opacity: 0.001;
    }
  </style>
  