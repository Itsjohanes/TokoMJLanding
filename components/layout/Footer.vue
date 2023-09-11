<template>
  <footer class="bg-white">
    <div class="container mx-auto px-8">
      <div class="w-full flex flex-col md:flex-row py-6">
        <div class="flex-1 mb-6 text-black">
          <a
            class="text-pink-600 no-underline hover:no-underline font-bold text-2xl lg:text-4xl"
            href="#"
          >
            Toko Maju Jaya
          </a>
        </div>
        <div class="flex-1">
          <ul>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="#"
                class="no-underline hover:underline text-gray-800 hover:text-pink-500"
                >Pengembang</a
              >
            </li>
            <li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a
                href="https://wengdev.tech"
                class="no-underline hover:underline text-gray-800 hover:text-pink-500"
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "layout-footer",
});
</script>
