<template>
  <svg
    width="100%"
    height="284"
    xmlns="http://www.w3.org/2000/svg"
    class="custom-section-curved-top-5"
  >
    <path
      id="svg_2"
      fill="#eff1f3"
      stroke="#000"
      stroke-width="0"
      d="m-30.75698,18.18081c99.6013,28.33304 337.54319,327.06425 868.97187,168.96887c265.71434,-79.04769 585.03969,-5.59538 690.67474,14.9602c105.63504,20.55559 381.87048,2.11063 555.67444,-75.27753c86.90199,-38.69407 736.04117,-78.60276 742.95015,12.26524c6.90898,90.86801 -66.08835,361.6009 -103.97283,363.40912c-37.88449,1.80823 -2793.7397,-55.67435 -2792.62804,-56.56315"
    ></path>
  </svg>
  <section id="pricing" class="relative bg-primarybg py-10">
    <div class="container mx-auto text-center px-5 md:px-8 lg:px-28">
      <div class="my-10">
        <p class="font-light text-primarytxt">Harga Layanan</p>
        <h2 class="text-3xl font-bold text-slate-700">
          Rekomendasi Paket Layanan
        </h2>
      </div>
      <div class="grid grid-cols-1 lg:grid-cols-3 gap-10 my-20">
        <div class="bg-white rounded-md shadow px-10 py-16">
          <h4 class="text-2xl font-bold">Free Trial</h4>
          <ul class="flex flex-col gap-5 divide-y-2">
            <li class="font-bold">CREATOR WEB</li>
            <li>1 Website</li>
            <li>1 Halaman Web</li>
            <li>Tidak Dapat Menggunakan Alamat (Domain) Website Sendiri</li>

            <li class="font-bold">CREATOR SYSTEM</li>
            <li>1 Web API</li>
            <li>3 Proses Bisnis (Action) per Web API</li>
            <li>Maksimum 500 Requests per Proses Bisnis</li>
            <li>Tidak Dapat Menggunakan Alamat (Domain) Website Sendiri</li>
          </ul>
          <div class="mt-10">
            <NuxtLink
              class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
              to="/"
              >COBA GRATIS</NuxtLink
            >
          </div>
        </div>
        <div
          class="relative bg-primary rounded-md text-white px-10 py-16 overflow-hidden"
        >
          <span
            class="absolute bg-[#cccccc] font-bold px-5 py-2 top-6 -right-16 w-52 rotate-45"
            >POPULAR</span
          >
          <div class="my-5">
            <h4 class="text-2xl font-bold">Early Stage</h4>
            <p class="text-slate-200/50 font-light">Description about</p>
          </div>
          <ul class="flex flex-col gap-5 divide-y-2">
            <li class="font-bold">CREATOR WEB</li>
            <li>1 Website</li>
            <li>4 Halaman Web</li>
            <li>Dapat Menggunakan Alamat (Domain) Website Sendiri</li>
            <li class="font-bold">CREATOR SYSTEM</li>
            <li>1 Web API</li>
            <li>10 Proses Bisnis (Action) per Web API</li>
            <li>Maksimum 1000 Requests per Proses Bisnis</li>
            <li>Dapat Menggunakan Alamat (Domain) Website Sendiri</li>
            <li>1x Meeting Schedule with Software Consultan</li>
          </ul>
          <div class="mt-10">
            <NuxtLink
              class="bg-inherit font-semibold border-2 border-white text-white hover:bg-white hover:text-slate-900 rounded-full py-4 px-7"
              to="/"
              >LANGGANAN</NuxtLink
            >
          </div>
          <img
            src="/img/dots/dots-group.png"
            alt="dots"
            class="absolute -bottom-12 -left-12"
          />
        </div>
        <div class="bg-white rounded-md shadow px-10 py-16">
          <div class="my-5">
            <h4 class="text-2xl font-bold">Business</h4>
            <p class="text-primarytxt font-light">Description about</p>
          </div>
          <ul class="flex flex-col gap-5 divide-y-2">
            <li class="font-bold">CREATOR WEB</li>
            <li>1 Website</li>
            <li>15 Halaman Web</li>
            <li>Dapat Menggunakan Alamat (Domain) Website Sendiri</li>
            <li class="font-bold">CREATOR SYSTEM</li>
            <li>1 Web API</li>
            <li>25 Proses Bisnis (Action) per Web API</li>
            <li>Maksimum 3000 Requests per Proses Bisnis</li>
            <li>Dapat Menggunakan Alamat (Domain) Website Sendiri</li>
            <li>1x Meeting Schedule with Software Consultants</li>
          </ul>
          <div class="mt-10">
            <NuxtLink
              class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
              to="/"
              >LANGGANAN</NuxtLink
            >
          </div>
        </div>
      </div>
    </div>
    <div class="container mx-auto px-5 md:px-8 lg:px-28">
      <div
        class="bg-white flex flex-col xl:flex-row gap-8 justify-center items-center rounded-md border-t-4 border-primary shadow py-12"
      >
        <p class="text-center text-lg text-primarytxt">
          Belum menemukan pilihan layanan yang sesuai? Lihat lebih lengkap di
          halaman <strong>Pricing</strong> kami!
        </p>
        <div class="mx-5">
          <NuxtLink
            class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
            to="/"
            >Pelajari Lebih Lanjut</NuxtLink
          >
        </div>
      </div>
    </div>
    <div class="xl:-mb-32 xl:-mt-48 -mb-10">
      <svg width="100%" height="600px" xmlns="http://www.w3.org/2000/svg">
        <path
          id="svg_1"
          d="m-12.66406,442.40068c352.72654,-76.36348 565.45337,5.45453 696.36219,19.99996c130.90882,14.54542 270.90852,-23.63632 367.27196,-47.27263c96.36344,-23.63631 379.99921,-154.54513 527.27163,-209.09047c147.27242,-54.54535 381.813,-92.55755 406.36076,-99.00598c12.27388,-3.22421 917.96684,-113.93032 715.00991,10.61478c-202.95693,124.5451 -210.46055,521.28714 -198.64021,540.29354c11.82034,19.0064 -2500.90899,-15.53962 -2500.0019,-16.36399c-0.90709,0.82437 -9.99798,-180.99343 -9.09089,-181.8178"
          stroke-opacity="null"
          stroke-width="0"
          stroke="#000"
          fill="#f7f8f9"
        ></path>
        <path
          id="svg_2"
          d="m-116.90461,507.88064c314.5448,-112.72704 523.63527,-21.81814 878.17999,12.72724c354.54471,34.54538 632.72595,-225.45407 978.17978,-294.54484c172.72691,-34.54538 291.36195,-62.7275 368.52007,-78.40952c77.15812,-15.68202 352.84215,-22.50036 359.66142,-7.04537c13.63854,30.90997 97.72734,614.54347 50.90961,639.99858c-46.81772,25.4551 -855.68236,4.54593 -1433.63569,1.81866c-577.95334,-2.72727 -1155.90718,-5.45466 -1155.45364,-5.45491"
          stroke-opacity="null"
          stroke-width="0"
          stroke="#000"
          fill="#fbfcfc"
        ></path>
        <path
          id="svg_3"
          d="m-115.93584,623.27542c234.54496,-132.72699 429.09001,-112.72703 678.1804,-83.63619c249.09039,29.09085 389.09011,30.90903 656.36228,-107.2725c267.27217,-138.18153 816.36193,-207.2723 1121.81584,-170.90873c305.45391,36.36356 -292.72666,-19.99996 -293.63778,-18.18228c71.36548,8.18218 627.05432,68.63506 626.48637,265.22584c-0.56794,196.59079 -20.11364,456.59134 -31.02284,531.13767c-10.90919,74.54633 -1561.82313,-36.3646 -1565.45948,-34.54642c-3.63636,1.81818 -1249.08831,-1.81818 -1248.18122,-1.81869c-0.90709,0.00051 39.09282,-234.54445 39.99992,-234.54496c-0.9071,0.00051 -4.54345,-76.36297 -3.63636,-76.36348"
          stroke-opacity="null"
          stroke-width="0"
          stroke="#000"
          fill="#ffffff"
        ></path>
      </svg>
    </div>
    <img
      src="/img/dots/dots-group.png"
      alt="dots"
      class="absolute bottom-20 left-[20%] -rotate-90"
    />
  </section>
</template>
