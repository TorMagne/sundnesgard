<template>
  <nav>
    <div class="navbar bg-[#2D545E] shadow-sm">
      <div class="container flex mx-auto items-center">
        <div class="flex-1">
          <NuxtLink to="/">
            <img src="~/assets/img/logo.png" alt="Sundnes gård logo" class="h-16" />
          </NuxtLink>
        </div>
        <div class="flex-none">
          <button class="btn btn-square btn-ghost hidden">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              class="inline-block h-5 w-5 stroke-current"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z"
              ></path>
            </svg>
          </button>
        </div>
      </div>
    </div>
  </nav>
  <main class="mx-auto">
    <!-- hero -->
    <section class="mb-20">
      <div class="hero min-h-[80vh] bg-base-200">
        <div class="container max-auto px-4 gap-20 flex flex-col md:flex-row-reverse">
          <!-- Bildeside -->
          <div class="w-full lg:w-1/2">
            <img
              src="/assets/img/hero.jpg"
              alt="Sundnes Gård"
              class="w-full h-[300px] sm:h-[400px] md:h-[500px] lg:h-full object-cover rounded-lg shadow-2xl"
            />
          </div>

          <!-- Tekstside -->
          <div class="w-full lg:w-1/2">
            <h1 class="text-3xl lg:text-5xl font-bold">
              Velkommen til Sundnes Gård – et unikt sted for uforglemmelige øyeblikk.
            </h1>
            <p class="py-6">
              Vi tilbyr utleie til bryllup, konfirmasjoner, bursdager og andre arrangement i rolige,
              landlige omgivelser.
            </p>
            <div>
              <a
                href="#kontakt"
                class="mr-4 btn bg-[#2D545E] border-2 border-transparent text-white hover:bg-transparent hover:text-black hover:border-2 hover:border-[#2D545E] transition duration-300 ease-in-out"
              >
                Kontakt oss
              </a>
              <a
                href="#selskap"
                class="btn bg-[#2D545E] border-2 border-transparent text-white hover:bg-transparent hover:text-black hover:border-[#2D545E] transition duration-300 ease-in-out"
              >
                Selskap
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- intro -->
    <section class="grid gap-3 mb-20 justify-center container mx-auto px-4">
      <p class="break-normal text-gray-500 opacity-90">
        <span class="font-bold text-2xl text-black">Sundnes Gård</span> ligger vakkert til ved
        <span class="underline decoration-sky-500 decoration-2">
          Borgenfjorden i Inderøy kommune i Trøndelag.</span
        >
      </p>
      <p class="break-normal text-gray-500 opacity-90">
        Her drives allsidig utleie av selskaps- og møtelokaler i historiske omgivelser fra tidlig
        1700-tallet.
      </p>
      <p class="break-normal text-gray-500 opacity-90">
        Den unike, personlige gårdssjarmen gir en varm ramme for bryllup, konfirmasjon, bursdager og
        firmaarrangement, og legger til rette for uforglemmelige opplevelser.
      </p>
      <p class="break-normal text-gray-500 opacity-90">
        Alt fra lokal kulturarv og levende historiefortellinger til storslått natur gjør Sundnes
        Gård til det lille ekstra for alle gjester
      </p>
    </section>
    <!-- selskap -->
    <section class="bg-base-200 mb-20" id="selskap">
      <div class="container mx-auto px-4 grid grid-cols-1 md:grid-cols-2 gap-20 py-20">
        <!-- Tekstside -->
        <div class="flex flex-col justify-center gap-2">
          <h2 class="text-3xl lg:text-5xl font-bold mb-4">Selskap</h2>
          <p>
            Sundnes Gård har gleden av å tilby utleie av selskapslokaler tilpasset ulike typer
            arrangementer.
          </p>
          <p>
            Lokalene passer for grupper fra 10 og opp til 150 personer, og egner seg godt til alt
            fra jubileumsfester, bryllup og konfirmasjoner, til slektsstevner, grillfester,
            pensjonisttreff og barnehagebesøk.
          </p>
          <p>
            Vi tilbyr kortreist, norsk mat – og et vertskap som legger vekt på varme og kvalitet.
          </p>
        </div>

        <!-- Bildeside -->
        <div>
          <img
            src="/assets/img/storsalen.jpg"
            alt="Sundnes Gård"
            class="w-full h-[300px] sm:h-[400px] md:h-[500px] lg:h-full object-cover rounded-lg shadow-2xl"
          />
        </div>
      </div>
    </section>

    <section class="container mx-auto px-4 py-16" id="kontakt">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
        <!-- Kontaktinfo -->
        <div class="order-1 md:order-0">
          <h2 class="text-3xl lg:text-5xl font-bold mb-6">Kontakt oss</h2>

          <!-- E-post -->
          <p class="flex items-center mb-4 text-gray-700">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 24 24"
              class="w-6 h-6 mr-3"
            >
              <path
                fill-rule="evenodd"
                d="M17.834 6.166a8.25 8.25 0 1 0 0 11.668.75.75 0 0 1 1.06 1.06c-3.807 3.808-9.98 3.808-13.788 0-3.808-3.807-3.808-9.98 0-13.788 3.807-3.808 9.98-3.808 13.788 0A9.722 9.722 0 0 1 21.75 12c0 .975-.296 1.887-.809 2.571-.514.685-1.28 1.179-2.191 1.179-.904 0-1.666-.487-2.18-1.164a5.25 5.25 0 1 1-.82-6.26V8.25a.75.75 0 0 1 1.5 0V12c0 .682.208 1.27.509 1.671.3.401.659.579.991.579.332 0 .69-.178.991-.579.3-.4.509-.99.509-1.671a8.222 8.222 0 0 0-2.416-5.834ZM15.75 12a3.75 3.75 0 1 0-7.5 0 3.75 3.75 0 0 0 7.5 0Z"
                clip-rule="evenodd"
              />
            </svg>
            <a href="mailto:post@sundesgard.no" class="break-words hover:underline"
              >post@sundesgard.no</a
            >
          </p>

          <!-- Adresse -->
          <p class="flex items-center text-gray-700">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 24 24"
              class="w-6 h-6 mr-3"
            >
              <path
                fill-rule="evenodd"
                d="m11.54 22.351.07.04.028.016a.76.76 0 0 0 .723 0l.028-.015.071-.041a16.975 16.975 0 0 0 1.144-.742 19.58 19.58 0 0 0 2.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 0 0-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 0 0 2.682 2.282 16.975 16.975 0 0 0 1.145.742ZM12 13.5a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"
                clip-rule="evenodd"
              />
            </svg>
            <a
              href="https://maps.google.com/?q=Hamnavegen+51,7670+Inderøy"
              target="_blank"
              class="hover:underline"
            >
              Hamnavegen 51, 7670 Inderøy
            </a>
          </p>
        </div>

        <!-- Google Maps -->
        <div class="order-2 md:order-1 w-full h-[300px] sm:h-[400px] md:h-[450px]">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1757.1189785820638!2d11.25141061331205!3d63.87054667702739!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x466d618dc4d2e25d%3A0xebdf10ccc7f3c491!2sHamnavegen%2051%2C%207670%20Inder%C3%B8y!5e0!3m2!1sen!2sno!4v1749224371634!5m2!1sen!2sno"
            class="w-full h-full rounded-lg shadow-md"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
      </div>
    </section>
  </main>

  <footer class="bg-[#2D545E] text-neutral-content">
    <div
      class="container mx-auto px-4 py-6 flex flex-col md:flex-row items-center justify-between gap-4"
    >
      <!-- Logo + Text -->
      <aside
        class="flex flex-col items-center md:flex-row md:items-center gap-4 text-center md:text-left"
      >
        <NuxtLink to="/">
          <img src="~/assets/img/logo.png" alt="Sundnes gård logo" class="h-16" />
        </NuxtLink>
        <p class="text-sm">Copyright © {{ currentYear }} – Alle rettigheter reservert</p>
      </aside>

      <!-- Socials -->
      <nav class="flex gap-4 justify-center">
        <a
          href="https://www.facebook.com/profile.php?id=100085011034401"
          target="_blank"
          aria-label="Facebook"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current text-white hover:text-gray-300"
          >
            <path
              d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"
            ></path>
          </svg>
        </a>
      </nav>
    </div>
  </footer>
</template>

<script setup>
useHead({
  htmlAttrs: {
    class: 'scroll-smooth',
  },
});

const currentYear = new Date().getFullYear();
</script>
