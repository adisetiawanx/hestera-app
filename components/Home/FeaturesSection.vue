<template>
  <section id="features">
    <div
      class="container flex flex-col lg:flex-row justify-center items-center gap-20 px-3 md:px-8 lg:px-0 mx-auto lg:-mt-40 text-primarytxt"
    >
      <div class="flex-1 z-40">
        <div class="flex flex-col md:flex-row gap-10">
          <div class="flex flex-col gap-10 -mt-40">
            <div class="card text-center">
              <div class="flex justify-center">
                <img
                  src="/img/icons/drag_drop.svg"
                  width="100"
                  height="100"
                  alt="Drag and Drop"
                />
              </div>
              <div class="relative">
                <img
                  class="absolute -left-32 -z-10"
                  src="/img/dots/dots-group.png"
                />
                <h4 class="font-semibold text-lg text-slate-900 py-3">
                  Drag and Drop UI Editor
                </h4>
                <p>
                  Platform Hestara memiliki teknologi untuk membuat tampilan
                  antar muka aplikasi tanpa code program, kamu cukup menggunakan
                  editor dari Hestara untuk membuat tampilan aplikasi sesuai
                  dengan keinginanmu.
                </p>
              </div>
            </div>
            <div class="card text-center">
              <div class="flex justify-center">
                <img
                  src="/img/icons/api_creator.svg"
                  width="100"
                  height="100"
                  alt="Drag and Drop"
                />
              </div>
              <div class="relative">
                <h4 class="font-semibold text-lg text-slate-900 py-3">
                  API Creator
                </h4>
                <p>
                  Teknologi ini dapat memberi kemudahan dalam integrasi sistem
                  aplikasimu, dimana API akan di generate secara otomatis
                  berdasarkan visualisasi yang sudah kamu buat.
                </p>
                <div
                  class="circle -right-20 bottom-10 h-[25px] w-[25px] bg-[#e260b8]"
                ></div>
              </div>
            </div>
          </div>
          <div>
            <div class="card text-center">
              <div class="flex justify-center">
                <img
                  src="/img/icons/visual.svg"
                  width="100"
                  height="100"
                  alt="Drag and Drop"
                />
              </div>
              <div class="relative">
                <h4 class="font-semibold text-lg text-slate-900 py-3">
                  Logic Visualization
                </h4>
                <p>
                  Teknologi lainnya dari Hestara adalah dapat memvisualisasikan
                  tipe pengguna dan fitur yang dapat digunakan pada aplikasimu.
                  Teknologi Hestara akan memproses kode program secara otomatis
                  sesuai dengan visualisasi yang kamu buat.
                </p>
                <img
                  class="absolute -right-20 -bottom-20 -z-10"
                  src="/img/dots/dots-group.png"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex-1">
        <div class="max-w-[700px]">
          <div class="my-3">
            <h3 class="text-2xl font-semibold text-slate-900">
              Implementasikan Ide Bisnis Digitalmu Sekarang!
            </h3>
            <span class="text-sm">NO CODE PROGRAM</span>
          </div>
          <div class="my-3">
            <h5 class="text-lg my-5">
              Jangan biarkan pengembangan aplikasi menghambat ide bisnis
              digitalmu.
            </h5>
            <p class="font-light">
              Hestara hadir untuk memberikan solusi dan kemudahan untuk kamu
              yang ingin mengembangkan aplikasi secara profesional tanpa code
              program. Fitur-fitur pada platform Hestara memberikan kemudahan
              bagi kamu yang ingin mengembangkan bisnis digital agar menjadi
              sebuah aplikasi bisnis profesional.
            </p>
            <div class="mt-8">
              <NuxtLink
                class="bg-gradient font-semibold text-white rounded-full py-4 px-7"
                to="/"
                >Pilih Layanan</NuxtLink
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <svg
        id="wave"
        style="transform: rotate(0deg); transition: 0.3s"
        viewBox="0 0 1440 100"
        version="1.1"
        xmlns="http://www.w3.org/2000/svg"
      >
        <defs>
          <linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0">
            <stop stop-color="rgba(239, 241, 243, 1)" offset="0%"></stop>
            <stop stop-color="rgba(239, 241, 243, 1)" offset="100%"></stop>
          </linearGradient>
        </defs>
        <path
          style="transform: translate(0, 0px); opacity: 1"
          fill="url(#sw-gradient-0)"
          d="M0,80L20,81.7C40,83,80,87,120,78.3C160,70,200,50,240,35C280,20,320,10,360,13.3C400,17,440,33,480,43.3C520,53,560,57,600,63.3C640,70,680,80,720,76.7C760,73,800,57,840,56.7C880,57,920,73,960,75C1000,77,1040,63,1080,51.7C1120,40,1160,30,1200,33.3C1240,37,1280,53,1320,58.3C1360,63,1400,57,1440,48.3C1480,40,1520,30,1560,33.3C1600,37,1640,53,1680,55C1720,57,1760,43,1800,33.3C1840,23,1880,17,1920,18.3C1960,20,2000,30,2040,38.3C2080,47,2120,53,2160,51.7C2200,50,2240,40,2280,30C2320,20,2360,10,2400,5C2440,0,2480,0,2520,5C2560,10,2600,20,2640,23.3C2680,27,2720,23,2760,28.3C2800,33,2840,47,2860,53.3L2880,60L2880,100L2860,100C2840,100,2800,100,2760,100C2720,100,2680,100,2640,100C2600,100,2560,100,2520,100C2480,100,2440,100,2400,100C2360,100,2320,100,2280,100C2240,100,2200,100,2160,100C2120,100,2080,100,2040,100C2000,100,1960,100,1920,100C1880,100,1840,100,1800,100C1760,100,1720,100,1680,100C1640,100,1600,100,1560,100C1520,100,1480,100,1440,100C1400,100,1360,100,1320,100C1280,100,1240,100,1200,100C1160,100,1120,100,1080,100C1040,100,1000,100,960,100C920,100,880,100,840,100C800,100,760,100,720,100C680,100,640,100,600,100C560,100,520,100,480,100C440,100,400,100,360,100C320,100,280,100,240,100C200,100,160,100,120,100C80,100,40,100,20,100L0,100Z"
        ></path>
      </svg>
      <svg
        id="wave"
        style="transform: rotate(180deg); transition: 0.3s"
        viewBox="0 0 1440 100"
        version="1.1"
        xmlns="http://www.w3.org/2000/svg"
      >
        <defs>
          <linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0">
            <stop stop-color="rgba(239, 241, 243, 1)" offset="0%"></stop>
            <stop stop-color="rgba(239, 241, 243, 1)" offset="100%"></stop>
          </linearGradient>
        </defs>
        <path
          style="transform: translate(0, 0px); opacity: 1"
          fill="url(#sw-gradient-0)"
          d="M0,80L26.7,81.7C53.3,83,107,87,160,78.3C213.3,70,267,50,320,35C373.3,20,427,10,480,13.3C533.3,17,587,33,640,43.3C693.3,53,747,57,800,63.3C853.3,70,907,80,960,76.7C1013.3,73,1067,57,1120,56.7C1173.3,57,1227,73,1280,75C1333.3,77,1387,63,1440,51.7C1493.3,40,1547,30,1600,33.3C1653.3,37,1707,53,1760,58.3C1813.3,63,1867,57,1920,48.3C1973.3,40,2027,30,2080,33.3C2133.3,37,2187,53,2240,55C2293.3,57,2347,43,2400,33.3C2453.3,23,2507,17,2560,18.3C2613.3,20,2667,30,2720,38.3C2773.3,47,2827,53,2880,51.7C2933.3,50,2987,40,3040,30C3093.3,20,3147,10,3200,5C3253.3,0,3307,0,3360,5C3413.3,10,3467,20,3520,23.3C3573.3,27,3627,23,3680,28.3C3733.3,33,3787,47,3813,53.3L3840,60L3840,100L3813.3,100C3786.7,100,3733,100,3680,100C3626.7,100,3573,100,3520,100C3466.7,100,3413,100,3360,100C3306.7,100,3253,100,3200,100C3146.7,100,3093,100,3040,100C2986.7,100,2933,100,2880,100C2826.7,100,2773,100,2720,100C2666.7,100,2613,100,2560,100C2506.7,100,2453,100,2400,100C2346.7,100,2293,100,2240,100C2186.7,100,2133,100,2080,100C2026.7,100,1973,100,1920,100C1866.7,100,1813,100,1760,100C1706.7,100,1653,100,1600,100C1546.7,100,1493,100,1440,100C1386.7,100,1333,100,1280,100C1226.7,100,1173,100,1120,100C1066.7,100,1013,100,960,100C906.7,100,853,100,800,100C746.7,100,693,100,640,100C586.7,100,533,100,480,100C426.7,100,373,100,320,100C266.7,100,213,100,160,100C106.7,100,53,100,27,100L0,100Z"
        ></path>
      </svg>
    </div>
  </section>
</template>
