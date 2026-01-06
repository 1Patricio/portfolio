<template>
    <!-- Projeto 1 - PlugGo -->
  <div class="hero mt-2">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <div class="carousel rounded-box xl:w-fit lg:ml-24">
        <div class="carousel-item h-96">
          <img src="../assets/images/pluggo-1.png" alt="Imagem projeto pluggo 1"/>
        </div>
        <div class="carousel-item h-96">
          <img src="../assets/images/pluggo-2.jpeg" alt="Imagem projeto pluggo 2"/>
        </div>
        <div class="carousel-item h-96">
          <img src="../assets/images/pluggo-3.jpeg" alt="Imagem projeto pluggo 3"/>
        </div>
        <div class="carousel-item h-96">
          <img src="../assets/images/pluggo-4.png" alt="Imagem projeto pluggo 4"/>
        </div>
        <div class="carousel-item h-96">
          <img src="../assets/images/pluggo-5.jpeg" alt="Imagem projeto pluggo 5"/>
        </div>
      </div>

      <div>
        <h1 class="text-3xl font-bold sm:text-5xl">Plug Go!</h1>
        <h6 class="text-sm font-mono sm:text-sm mt-1">Aplicativo para reservas de eletropontos para carros elétricos</h6>
        <p class="py-6">
          Desenvolvi o Plug-Go, um aplicativo completo para reserva de pontos de recarga de veículos elétricos. Focado em boas práticas, utilizei injeção de dependência para um código escalável e de fácil manutenção, integração com <b>Firebase Auth</b> para autenticação segura e suporte a múltiplos idiomas (i18n). Um projeto que demonstra a construção de uma aplicação mobile robusta e moderna com <b>Flutter</b>. Para o backend, desenvolvi uma API feita em <b>Java</b>, SpringBoot e PostgreSQL.
        </p>

        <div class="flex items-center mr">
          <button class="btn bg-gray-700 text-white border-gray-700 mx-1">
            <img src="../assets/images/visualizar.png" alt="Icone Projetos" width="20" height="20">
            <a href="https://www.linkedin.com/feed/update/urn:li:activity:7404319833536049152/" target="_blank">Visualizar</a>
          </button>

          <div class="ml-2 flex">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="h-6 w-6 shrink-0 stroke-current">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
            </svg>
            <span class="ml-1">Repositório Privado</span>
          </div>
        </div>

        <div class="card-actions justify-start mt-2 md:justify-end md:mt-0">
          <div class="badge badge-outline">Flutter</div>
          <div class="badge badge-outline">Java</div>
          <div class="badge badge-outline">SpringBoot</div>
          <div class="badge badge-outline">PostgreSQL</div>
        </div>
      </div>
    </div>
  </div>

  <div class="my-8"/>

  <!-- Projeto 2 - Rick and Morty -->
  <div class="hero mt-2">
    <div class="hero-content flex-col lg:flex-row">
      <video width="640" height="360" controls muted autoplay loop class="lg:mr-4">
        <source src="../assets/videos/project2.mp4" type="video/mp4" />
        O seu navegador não suporta a tag de vídeo
      </video>
      <div>
        <h1 class="text-3xl font-bold sm:text-5xl">MVP Rick and Morty!</h1>
        <p class="py-6">
          Desenvolvi um MVP em <b>Vue.js</b> para buscar personagens e episódios da API Rick and Morty. Arquitetura componentizada (SFCs), roteamento organizado, layout reutilizávele e uso de DaisyUI | Tailwind para consistência visual. Segui boas práticas de SEO (meta tags), acessibilidade (roles semânticos) e carregamento assíncrono, com foco em código limpo, performance e escalabilidade
        </p>

        <button class="btn bg-black text-white border-black mx-1 mb-1">
          <svg aria-label="GitHub logo" width="16" height="16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path fill="white" d="M12,2A10,10 0 0,0 2,12C2,16.42 4.87,20.17 8.84,21.5C9.34,21.58 9.5,21.27 9.5,21C9.5,20.77 9.5,20.14 9.5,19.31C6.73,19.91 6.14,17.97 6.14,17.97C5.68,16.81 5.03,16.5 5.03,16.5C4.12,15.88 5.1,15.9 5.1,15.9C6.1,15.97 6.63,16.93 6.63,16.93C7.5,18.45 8.97,18 9.54,17.76C9.63,17.11 9.89,16.67 10.17,16.42C7.95,16.17 5.62,15.31 5.62,11.5C5.62,10.39 6,9.5 6.65,8.79C6.55,8.54 6.2,7.5 6.75,6.15C6.75,6.15 7.59,5.88 9.5,7.17C10.29,6.95 11.15,6.84 12,6.84C12.85,6.84 13.71,6.95 14.5,7.17C16.41,5.88 17.25,6.15 17.25,6.15C17.8,7.5 17.45,8.54 17.35,8.79C18,9.5 18.38,10.39 18.38,11.5C18.38,15.32 16.04,16.16 13.81,16.41C14.17,16.72 14.5,17.33 14.5,18.26C14.5,19.6 14.5,20.68 14.5,21C14.5,21.27 14.66,21.59 15.17,21.5C19.14,20.16 22,16.42 22,12A10,10 0 0,0 12,2Z"></path></svg>
          <a href="https://github.com/1Patricio/mvp-daisyui-vue" target="_blank">Repositório</a>
        </button>

        <button class="btn bg-gray-700 text-white border-gray-700 mx-1">
          <img src="../assets/images/visualizar.png" alt="Icone Projetos" width="20" height="20">
          <a href="https://rickandmortymvp.netlify.app/" target="_blank">Visualizar</a>
        </button>

        <div class="card-actions justify-end">
          <div class="badge badge-outline">Vue</div>
          <div class="badge badge-outline">DaisyUI</div>
          <div class="badge badge-outline">VueRouter</div>
          <div class="badge badge-outline">Vite</div>
        </div>
      </div>
    </div>
  </div>

</template>
