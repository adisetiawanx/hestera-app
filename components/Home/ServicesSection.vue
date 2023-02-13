<template>
  <section id="services">
    <div class="relative container mx-auto text-center my-20">
      <div class="circle bg-[#b9b9b9] h-6 w-6 -top-14 right-[35%]">
        <div class="circle bg-[#e4e4e4] h-4 w-4 -bottom-2 -left-5"></div>
        <div class="circle bg-[#e4e4e4] h-3 w-3 top-0 -left-3"></div>
      </div>
      <div class="circle bg-[#b84ed9] h-6 w-6 top-10 right-10">
        <div class="circle bg-[#b9b9b9] h-4 w-4 top-4 -right-4"></div>
        <div class="circle bg-[#e4e4e4] h-3 w-3 top-7 -right-7"></div>
      </div>
      <div class="mb-14 px-3 md:px-8 lg:px-0">
        <h2 class="text-3xl font-bold my-4 text-slate-700">Layanan Kami</h2>
        <p class="font-light text-primarytxt">
          Sesuaikan layanan yang kamu butuhkan untuk digitalisasi bisnismu
        </p>
      </div>
      <div
        class="flex flex-col lg:flex-row justify-center gap-8 my-10 px-3 md:px-8 lg:px-0"
      >
        <div class="relative card max-w-[400px] mx-auto lg:mx-0">
          <img
            src="/img/dots/dots-group-3.png"
            alt="dots"
            class="absolute -left-16 -top-16 -z-10"
          />
          <h4 class="text-xl font-semibold mb-3">Creator Web</h4>
          <p class="text-primarytxt">
            Merupakan platform yang membantu User dalam membuat tampilan website
            secara <strong>full custom</strong> untuk menghasilkan code program
            dan tampilan website secara <strong>otomatis</strong>.
          </p>
          <div class="mt-10">
            <NuxtLink
              class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
              to="/creator-web"
              >Pelajari Lebih Lanjut</NuxtLink
            >
          </div>
        </div>
        <div class="card lg:-mb-14 lg:mt-14 max-w-[400px] mx-auto lg:mx-0">
          <h4 class="text-xl font-semibold mb-3">Creator System</h4>
          <p class="text-primarytxt">
            Merupakan platform yang membantu User dalam memvisualisasikan
            kebutuhan dan <strong>logika</strong> aplikasi untuk diproses
            menjadi <strong>kode program</strong> dan API secara
            <strong>otomatis</strong>.
          </p>
          <div class="mt-10">
            <NuxtLink
              class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
              to="/creator-system"
              >Pelajari Lebih Lanjut</NuxtLink
            >
          </div>
        </div>
        <div class="card max-w-[400px] mx-auto lg:mx-0">
          <h4 class="text-xl font-semibold mb-3">Software Consultant</h4>
          <p class="text-primarytxt">
            Merupakan service yang disediakan oleh Hestara untuk kamu yang
            membutuhkan brainstroming ide atau diskusi mengenai konsep aplikasi
            yang akan dibangun.
          </p>
          <div class="mt-10">
            <a
              class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
              href="tel:+6285162900414"
              >Hubungi Kami</a
            >
          </div>
        </div>
      </div>
      <div class="relative circle bg-[#e260b8] h-12 w-12 -bottom-32 left-14">
        <div class="circle bg-[#b9b9b9] h-5 w-5 -bottom-4"></div>
        <div class="circle bg-[#e4e4e4] h-4 w-4 -bottom-2 -left-5"></div>
        <div class="circle bg-[#e4e4e4] h-3 w-3 -bottom-6 -left-5"></div>
      </div>
    </div>
  </section>
</template>
