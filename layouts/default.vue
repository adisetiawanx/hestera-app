<template>
  <header class="bg-primarybg">
    <div id="top_header" class="border-b-2 md:border">
      <div class="container flex justify-between items-center mx-auto">
        <div class="flex gap-5 text-sm text-primarytxt">
          <span class="m-4 md:m-0">info@hestara.app</span>
          <span class="hidden md:inline">Mon - Fri 9:00am - 5:00pm</span>
        </div>
        <div
          class="hidden md:inline bg-[#4ed9b8] hover:bg-[#40b297] py-3 px-5 cursor-pointer"
        >
          <span class="text-white font-semibold">(+62) 851-6290-0414</span>
        </div>
      </div>
    </div>
    <div id="main_header" class="border-b-2 md:border">
      <div
        class="relative container mx-auto flex justify-between items-center py-7"
      >
        <div class="mx-3 md:mx-0">
          <img src="img/logo.svg" alt="Hestara" width="150" />
        </div>
        <nav class="mx-3 md:mx-0">
          <button
            @click="isShowMenu = !isShowMenu"
            class="bg-primary rounded py-1 px-2 md:hidden"
          >
            <span class="material-symbols-outlined text-white"> menu </span>
          </button>
          <ul
            class="md:flex px-3 md:px-0 justify-center items-center gap-5 text-primarytxt"
            :class="
              isShowMenu
                ? 'absolute flex-col top-[105px] right-0 left-0 w-full bg-primarybg py-5'
                : 'hidden'
            "
          >
            <li class="text-primary font-semibold my-5 md:my-0">
              <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li
              class="relative my-5 md:my-0"
              @click="isShowProducts = !isShowProducts"
            >
              <span class="cursor-pointer hover:text-primary"
                >Our Products
              </span>

              <ul
                class="md:absolute flex-col gap-2 bg-white rounded-md border border-[#c5c6c8]"
                :class="isShowProducts ? 'block' : 'hidden'"
              >
                <li class="hover:bg-primarybg hover:text-primary p-3">
                  <NuxtLink to="/creator-web">Hestera Creator Web</NuxtLink>
                </li>
                <li class="hover:bg-primarybg hover:text-primary px-3 pb-3">
                  <NuxtLink to="/creator-system"
                    >Hestera Creator System</NuxtLink
                  >
                </li>
              </ul>
            </li>
            <li class="hover:text-primary my-5 md:my-0">
              <NuxtLink to="/pricing">Pricing Plan</NuxtLink>
            </li>
            <li class="hover:text-primary my-5 md:my-0">
              <NuxtLink to="/case-studies">Case Studies</NuxtLink>
            </li>
            <li class="hover:text-primary my-5 md:my-0">
              <NuxtLink to="/careers">Careers</NuxtLink>
            </li>
            <li class="my-5 md:my-0">
              <NuxtLink
                to="/admin"
                class="bg-gradient font-semibold text-white rounded-full py-2 px-4"
              >
                Admin Area
              </NuxtLink>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
  <slot />
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    let isShowProducts = ref(false);
    let isShowMenu = ref(false);

    return {
      isShowProducts,
      isShowMenu,
    };
  },
});
</script>
