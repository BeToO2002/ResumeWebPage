<script setup lang="ts">
import { ref } from "vue";
</script>

<template>
  <div class="min-h-screen w-full bg-gray-200">
    <div class="max-w-4xl mx-auto p-6 md:py-12">
      <!-- Header -->
      <div class="flex items-center justify-between mb-8">
        <p class="font-bold text-3xl text-gray-800">Humberto Valenzuela</p>
        <nav>
          <ul class="flex gap-4">
            <li>
              <a
                href="https://github.com/BeToO2002"
                target="_blank"
                rel="noopener noreferrer"
                class="text-gray-600 hover:text-indigo-600 transition-colors"
              >
                <svg
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-6 w-6 fill-current"
                >
                  <title>GitHub</title>
                  <path
                    d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                  />
                </svg>
              </a>
            </li>
            <li>
              <a
                href="humbertovalfig@gmail.com"
                target="_blank"
                rel="noopener noreferrer"
                class="text-gray-600 hover:text-indigo-600 transition-colors"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  class="h-6 w-6"
                >
                  <path
                    fill-rule="evenodd"
                    d="M17.834 6.166a8.25 8.25 0 1 0 0 11.668.75.75 0 0 1 1.06 1.06c-3.807 3.808-9.98 3.808-13.788 0-3.808-3.807-3.808-9.98 0-13.788 3.807-3.808 9.98-3.808 13.788 0A9.722 9.722 0 0 1 21.75 12c0 .975-.296 1.887-.809 2.571-.514.685-1.28 1.179-2.191 1.179-.904 0-1.666-.487-2.18-1.164a5.25 5.25 0 1 1-.82-6.26V8.25a.75.75 0 0 1 1.5 0V12c0 .682.208 1.27.509 1.671.3.401.659.579.991.579.332 0 .69-.178.991-.579.3-.4.509-.99.509-1.671a8.222 8.222 0 0 0-2.416-5.834ZM15.75 12a3.75 3.75 0 1 0-7.5 0 3.75 3.75 0 0 0 7.5 0Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </a>
            </li>
          </ul>
        </nav>
      </div>

      <div class="space-y-6">
        <!-- Hero card -->
        <div
          class="p-8 bg-blue-500 rounded-3xl flex items-center gap-8 shadow-sm"
        >
          <div class="bg-white p-2 rounded-2xl shrink-0">
            <img
              class="w-40 h-40 md:w-48 md:h-48 rounded-xl object-cover"
              src="../img/perfil.png"
              alt="Perfil"
            />
          </div>
          <div class="text-white">
            <p class="font-bold text-3xl">Humberto Valenzuela</p>
            <p class="text-xl opacity-90">Web Developer</p>
            <div class="pt-2">
              <button
                class="font-medium bg-gray-200 text-black p-2 rounded-4xl hover:bg-gray-500 hover:text-white duration-200"
              >
                Download CV
              </button>
            </div>
          </div>
        </div>

        <!-- Info card -->
        <div class="bg-white p-8 rounded-3xl shadow-sm">
          <h2 class="font-bold text-2xl text-gray-800 mb-2">About Me</h2>
          <p class="text-gray-600 leading-relaxed mb-6">
            Web developer with a solid foundation in mobile technologies and
            databases.
          </p>

          <!-- ✅ Grid corregido: 2 columnas simples, sin ml-20 hardcodeado -->
          <div class="grid grid-cols-2 gap-y-2 gap-x-4 mb-6 max-w-xs">
            <span class="text-gray-500 font-medium">Age</span>
            <span class="text-gray-800 font-semibold">24</span>

            <span class="text-gray-500 font-medium">Phone</span>
            <span class="text-gray-800 font-semibold">6622781465</span>

            <span class="text-gray-500 font-medium">Address</span>
            <span class="text-gray-800 font-semibold">Sonora, Mexico</span>
          </div>

          <hr class="border-t border-gray-300 mb-6" />

          <!-- ✅ Sección eliminada (estaba vacía y duplicada) -->
          <h2 class="font-bold text-2xl text-gray-800 mb-4">Skills</h2>
          <div class="flex flex-wrap gap-2 pb-6">
            <span
              class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
              >Vue.js</span
            >
            <span
              class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
              >TypeScript</span
            >
            <span
              class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
              >Tailwind CSS</span
            >
            <span
              class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
              >SQL</span
            >
            <span
              class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
              >Mobile Dev</span
            >
          </div>
          <hr class="border-t border-gray-300 mb-6" />

          <div>
            <h2 class="font-bold text-2xl text-gray-800 mb-2">Projects</h2>

            <div>
              <div class="p-4 bg-gray-50 border border-gray-200 rounded-3xl">
                <div class="flex grid-cols-2 justify-between">
                  <p class="font-bold text-2xl">Pruning Management System</p>
                  <a
                    href="https://github.com/BeToO2002"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="text-gray-600 hover:text-indigo-600 transition-colors"
                  >
                    <svg
                      role="img"
                      viewBox="0 0 24 24"
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-6 w-6 fill-current"
                    >
                      <title>GitHub</title>
                      <path
                        d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                      />
                    </svg>
                  </a>
                </div>

                <div>
                  <p>
                    Design and development of a comprehensive web platform for
                    the control, logging, and progress tracking of CFE pruning
                    maintenance. Full-Stack Architecture utilizing Vue.js,
                    TypeScript, and PHP for efficient data consumption.
                  </p>
                </div>
                <div class="flex flex-wrap gap-2 pt-2 pb-2">
                  <span
                    class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
                    >Vue.js</span
                  >
                  <span
                    class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
                    >TypeScript</span
                  >
                  <span
                    class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
                    >Tailwind CSS</span
                  >
                  <span
                    class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
                    >SQL</span
                  >
                  <span
                    class="bg-blue-50 text-blue-700 px-3 py-1 rounded-full text-sm font-medium"
                    >Mobile Dev</span
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
