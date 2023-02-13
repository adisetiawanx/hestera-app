<template>
  <header class="bg-primarybg">
    <div id="top_header" class="border-b-2 md:border">
      <div
        class="container flex justify-between items-center mx-auto md:px-8 lg:px-0"
      >
        <div class="flex gap-5 text-sm text-primarytxt">
          <a
            class="m-4 md:m-0 hover:underline hover:text-primary"
            href="mailto:hestara.app@gmail.com"
            >info@hestara.app</a
          >
          <span class="hidden md:inline">Mon - Fri 9:00am - 5:00pm</span>
        </div>
        <div
          class="hidden md:inline bg-[#4ed9b8] hover:bg-[#40b297] py-3 px-5 cursor-pointer"
        >
          <span class="text-white font-semibold"
            ><a href="tel:+6285162900414">(+62) 851-6290-0414</a></span
          >
        </div>
      </div>
    </div>
    <div id="main_header" class="border-b-2 md:border md:px-8 lg:px-0">
      <div
        class="relative container mx-auto flex justify-between items-center py-7"
      >
        <div class="mx-3 md:mx-0">
          <img src="img/logo.svg" alt="Hestara" width="150" />
        </div>
        <nav class="px-3 md:px-0 z-50">
          <button
            @click="isShowMenu = !isShowMenu"
            class="bg-primary rounded py-1 px-2 lg:hidden"
          >
            <span class="material-symbols-outlined text-white"> menu </span>
          </button>
          <ul
            class="lg:static lg:flex flex-col lg:flex-row px-3 md:px-0 justify-center items-center gap-5 text-primarytxt"
            :class="
              isShowMenu
                ? 'absolute  top-[105px] right-0 left-0 bg-primarybg py-5'
                : 'hidden'
            "
          >
            <li class="text-primary font-semibold my-5 lg:my-0">
              <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li
              class="relative my-5 lg:my-0"
              @click="isShowProducts = !isShowProducts"
            >
              <span class="cursor-pointer hover:text-primary"
                >Our Products
              </span>

              <ul
                class="md:absolute flex-col gap-2 bg-white rounded-md border border-[#c5c6c8] w-52"
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
            <li class="hover:text-primary my-5 lg:my-0">
              <NuxtLink to="/pricing">Pricing Plan</NuxtLink>
            </li>
            <li class="hover:text-primary my-5 lg:my-0">
              <NuxtLink to="/case-studies">Case Studies</NuxtLink>
            </li>
            <li class="hover:text-primary my-5 lg:my-0">
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

  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 1440 320"
    class="lg:-mt-12"
  >
    <path
      fill="#6f279c"
      fill-opacity="1"
      d="M0,128L40,144C80,160,160,192,240,202.7C320,213,400,203,480,192C560,181,640,171,720,176C800,181,880,203,960,213.3C1040,224,1120,224,1200,208C1280,192,1360,160,1400,144L1440,128L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"
    ></path>
  </svg>
  <footer class="bg-secondary text-sm">
    <div
      class="container lg:max-w-[70%] flex flex-col md:flex-row gap-10 mx-3 md:mx-auto text-white px-5 md:px-0 pb-20 border-b border-white/20"
    >
      <div class="max-w-[50%]">
        <h3 class="text-lg font-bold mb-3">TENTANG KAMI</h3>
        <p>
          Hestara merupakan platform pembuatan aplikasi tanpa kode pemrograman
          yang membantu pelaku bisnis pemula (startup), individu (peneliti) dan
          organisasi dalam mengembangkan aplikasi secara cepat dan dinamis.
        </p>
      </div>
      <div class="flex-auto">
        <h3 class="text-lg font-bold mb-3">LINK PENTING</h3>
        <ul class="flex flex-col gap-1">
          <li class="hover:underline underline-offset-2">
            <NuxtLink to="/creator-web">Hestara Creator Web</NuxtLink>
          </li>
          <li class="hover:underline underline-offset-2">
            <NuxtLink to="/creator-system">Hestara Creator System</NuxtLink>
          </li>
          <li class="hover:underline underline-offset-2">
            <NuxtLink to="/pricing">Pricing Plan</NuxtLink>
          </li>
        </ul>
      </div>
      <div class="flex-auto">
        <h3 class="text-lg font-bold mb-3">CONTACT US</h3>
        <ul class="flex flex-col gap-1">
          <li>Jalan Bali Cliff No. 33A, Ungasan, Kuta Selatan</li>
          <li><a href="tel:+6285162900414">Phone: (+62) 851-6290-0414</a></li>
          <li><a href="mailto:info@hestara.app">Email: info@hestara.app</a></li>
        </ul>
      </div>
    </div>
    <div class="container mx-auto flex justify-center items-center py-5">
      <span class="text-white/50 text-sm"
        >Hestara © Copyright 2023. All Rights Reserved.</span
      >
    </div>
  </footer>
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
