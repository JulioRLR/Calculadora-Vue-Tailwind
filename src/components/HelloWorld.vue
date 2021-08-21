<template>
  <div class="min-h-screen bg-purple-300 flex items-center justify-center">
    <div class="bg-gray-800 border-2 border-gray-900 shadow-2xl rounded-lg">
      <form class="border-b-2 border-gray-900">
        <input
          type="number"
          class="
            bg-transparent
            p-8
            rounded-t-lg
            outline-none
            focus:bg-gray-700
            text-3xl text-right text-white
            font-mono
          "
        />
      </form>
      <div class="p-6 text-gray-800 grid grid-cols-4 gap-4 text-xl">
        <button
          class="font-mono col-span-3 bg-red-500 hover:bg-red-400 rounded p-5"
        >
          C
        </button>
        <button class="font-mono bg-purple-500 hover:bg-purple-400 rounded p-5">
          &divide;
        </button>

        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          1
        </button>
        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          2
        </button>
        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          3
        </button>
        <button class="font-mono bg-purple-500 hover:bg-purple-400 rounded p-5">
          &times;
        </button>

        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          4
        </button>
        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          5
        </button>
        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          6
        </button>
        <button class="font-mono bg-purple-500 hover:bg-purple-400 rounded p-5">
          &minus;
        </button>

        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          7
        </button>
        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          8
        </button>
        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          9
        </button>
        <button class="font-mono bg-purple-500 hover:bg-purple-400 rounded p-5">
          &plus;
        </button>

        <button class="font-mono bg-pink-300 hover:bg-pink-400 rounded p-5">
          0
        </button>
        <button
          class="
            font-mono
            col-span-3
            bg-green-400
            hover:bg-green-600
            rounded
            p-5
          "
        >
          &equals;
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
import { defineProps, reactive } from "vue";

defineProps({
  msg: String,
});
</script>

<style scoped>

</style>
